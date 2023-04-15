# Framework7_Cordova
Create Android Apps with Framework 7 and Cordova

#Komponen
1. Nodejs Version
https://nodejs.org/en/download
2. Npm Version
4. Install Framework7
5. Install Cordova

#Step instalasi
1. validasi nodejs & npm via cli
cli : nodejs --version
cli : npm --version
2. create folder mkdir
3. Install cordova via cli global system for building android extension .apk 
cli : npm install –g cordova
4. Install framework7 via cli global system for building layout android my apps
cli : npm install -g framework7-cli — -unsafe-per=true –allow-root
5. Create component framework7
cli : framework7 create
6. install npm via cli
cli : npm install
7. Start npm via cli
cli : npm start
8. View log
#end


E:\fipmo.id_aplikasi>npm install cordova
npm WARN deprecated @npmcli/move-file@1.1.2: This functionality has been moved to @npmcli/fs
npm WARN deprecated stringify-package@1.0.1: This module is not used anymore, and has been replaced by @npmcli/package-json
npm WARN deprecated har-validator@5.1.5: this library is no longer supported
npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142

added 455 packages, and audited 602 packages in 1m

88 packages are looking for funding
  run `npm fund` for details

13 moderate severity vulnerabilities

To address all issues, run:
  npm audit fix

Run `npm audit` for details.

E:\fipmo.id_aplikasi>npm audit
# npm audit report

got  <11.8.5
Severity: moderate
Got allows a redirect to a UNIX socket - https://github.com/advisories/GHSA-pfrx-2q88-qq97
fix available via `npm audit fix --force`
Will install cordova@6.1.1, which is a breaking change
node_modules/got
  package-json  <=6.5.0
  Depends on vulnerable versions of got
  node_modules/package-json
    latest-version  0.2.0 - 5.1.0
    Depends on vulnerable versions of package-json
    node_modules/latest-version
      update-notifier  0.2.0 - 5.1.0
      Depends on vulnerable versions of latest-version
      node_modules/update-notifier
        cordova  3.1.0-0.1.0 - 3.5.0-0.2.0 || 4.0.1 || >=5.4.0
        Depends on vulnerable versions of cordova-create
        Depends on vulnerable versions of cordova-lib
        Depends on vulnerable versions of insight
        Depends on vulnerable versions of update-notifier
        node_modules/cordova

request  *
Severity: moderate
Server-Side Request Forgery in Request - https://github.com/advisories/GHSA-p8p7-x288-28g6
fix available via `npm audit fix --force`
Will install cordova@6.1.1, which is a breaking change
node_modules/request
  insight  *
  Depends on vulnerable versions of request
  node_modules/insight
  node-gyp  <=7.1.2
  Depends on vulnerable versions of request
  node_modules/node-gyp
    @npmcli/run-script  1.1.1 - 1.8.6
    Depends on vulnerable versions of node-gyp
    node_modules/@npmcli/run-script
      pacote  11.1.5 - 11.3.5
      Depends on vulnerable versions of @npmcli/run-script
      node_modules/pacote
        cordova-fetch  3.0.1-nightly.2020.4.13.787574b1 - 3.1.1-nightly.2023.3.27.d7f5822a
        Depends on vulnerable versions of pacote
        node_modules/cordova-fetch
          cordova-create  1.1.3-nightly.2017.12.15.8ff490ce - 1.1.3-nightly.2018.3.17.8ff490ce || 4.0.0-nightly.2021.11.2.70bc862c - 4.1.1-nightly.2023.3.27.002f2c57
          Depends on vulnerable versions of cordova-fetch
          node_modules/cordova-create
          cordova-lib  7.0.2-nightly.2017.5.9.be7f7ac6 - 7.0.2-nightly.2017.9.24.e50c9b60 || 7.1.1-nightly.2017.10.10.708da2b8 - 7.1.1-nightly.2017.12.14.8ad0a8b9 || 8.0.1-nightly.2017.12.17.33ef33af - 8.0.1-nightly.2018.9.8.1bc9dd05 || 9.0.0-nightly.2018.9.13.87e9f5cd - 9.0.0-nightly.2019.2.17.7a5d4826 || 9.0.2-nightly.2019.4.2.c017729d - 10.0.0-nightly.2020.6.3.7a20be8b || 10.0.1-nightly.2020.7.28.1d98b57a - 12.0.0-nightly.2023.3.27.7f8b2d01
          Depends on vulnerable versions of cordova-fetch
          node_modules/cordova-lib

13 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force

E:\fipmo.id_aplikasi>npm audit fix --force
npm WARN using --force Recommended protections disabled.
npm WARN audit Updating cordova to 6.1.1, which is a SemVer major change.
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm WARN deprecated cryptiles@0.2.2: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated xmldom@0.1.31: Deprecated due to CVE-2021-21366 resolved in 0.5.0
npm WARN deprecated boom@0.4.2: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated sntp@0.2.4: This module moved to @hapi/sntp. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm WARN deprecated node-uuid@1.3.3: Use uuid module instead
npm WARN deprecated querystring@0.2.0: The querystring API is considered Legacy. new code should use the URLSearchParams API instead.
npm WARN deprecated hoek@0.9.1: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated request@2.47.0: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated uuid@2.0.3: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm WARN deprecated tar@1.0.2: This version of tar is no longer supported, and will not receive security updates. Please upgrade asap.
npm WARN deprecated hawk@1.1.1: This module moved to @hapi/hawk. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.

added 221 packages, removed 292 packages, changed 59 packages, and audited 763 packages in 2m

70 packages are looking for funding
  run `npm fund` for details

# npm audit report

bl  <1.2.3
Severity: moderate
Remote Memory Exposure in bl - https://github.com/advisories/GHSA-pp7h-53gx-mx7r
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/bl
node_modules/npm/node_modules/request/node_modules/bl
  request  *
  Depends on vulnerable versions of bl
  Depends on vulnerable versions of form-data
  Depends on vulnerable versions of hawk
  Depends on vulnerable versions of qs
  Depends on vulnerable versions of tunnel-agent
  node_modules/npm/node_modules/request
  node_modules/request
    cordova-lib  <=9.0.0-nightly.2018.9.17.c0fcda72 || 9.0.2-nightly.2019.4.2.c017729d - 10.0.0-nightly.2020.6.3.7a20be8b || 10.0.1-nightly.2020.7.28.1d98b57a - 10.0.1-nightly.2020.8.19.1d98b57a
    Depends on vulnerable versions of cordova-common
    Depends on vulnerable versions of cordova-js
    Depends on vulnerable versions of npm
    Depends on vulnerable versions of plist
    Depends on vulnerable versions of request
    Depends on vulnerable versions of shelljs
    Depends on vulnerable versions of tar
    Depends on vulnerable versions of underscore
    Depends on vulnerable versions of xcode
    node_modules/cordova-lib
      cordova  0.0.0-fake || >=3.1.0-0.1.0
      Depends on vulnerable versions of cordova-common
      Depends on vulnerable versions of cordova-lib
      Depends on vulnerable versions of underscore
      Depends on vulnerable versions of update-notifier
      node_modules/cordova
    node-gyp  <=7.1.2
    Depends on vulnerable versions of request
    Depends on vulnerable versions of tar
    node_modules/npm/node_modules/node-gyp
      npm  <=8.5.4 || 8.19.0 - 8.19.2 || 9.0.0-pre.0 - 9.0.0-pre.6
      Depends on vulnerable versions of chownr
      Depends on vulnerable versions of fstream
      Depends on vulnerable versions of hosted-git-info
      Depends on vulnerable versions of ini
      Depends on vulnerable versions of minimatch
      Depends on vulnerable versions of mkdirp
      Depends on vulnerable versions of node-gyp
      Depends on vulnerable versions of npm-registry-client
      Depends on vulnerable versions of npm-user-validate
      Depends on vulnerable versions of request
      Depends on vulnerable versions of tar
      node_modules/npm
    npm-registry-client  *
    Depends on vulnerable versions of request
    node_modules/npm/node_modules/npm-registry-client

brace-expansion  <1.1.7
Severity: high
ReDoS in brace-expansion - https://github.com/advisories/GHSA-832h-xg76-4gv6
fix available via `npm audit fix`
node_modules/cordova-lib/node_modules/brace-expansion
node_modules/npm/node_modules/minimatch/node_modules/brace-expansion

chownr  <1.1.0
Time-of-check Time-of-use (TOCTOU) Race Condition in chownr - https://github.com/advisories/GHSA-c6rq-rjc2-86v2
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/chownr

cryptiles  <=4.1.1
Severity: critical
Insufficient Entropy in cryptiles - https://github.com/advisories/GHSA-rq8g-5pc5-wrhr
Depends on vulnerable versions of boom
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/cryptiles
node_modules/npm/node_modules/request/node_modules/hawk/node_modules/cryptiles
  hawk  <=9.0.0
  Depends on vulnerable versions of boom
  Depends on vulnerable versions of cryptiles
  Depends on vulnerable versions of hoek
  Depends on vulnerable versions of sntp
  node_modules/hawk
  node_modules/npm/node_modules/request/node_modules/hawk

extend  3.0.0 - 3.0.1
Severity: moderate
Prototype Pollution in extend - https://github.com/advisories/GHSA-qrmc-fj45-qfc2
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/extend

fstream  <1.0.12
Severity: high
Arbitrary File Overwrite in fstream - https://github.com/advisories/GHSA-xf7w-r453-m56c
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/fstream

got  <11.8.5
Severity: moderate
Got allows a redirect to a UNIX socket - https://github.com/advisories/GHSA-pfrx-2q88-qq97
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/got
  package-json  <=6.5.0
  Depends on vulnerable versions of got
  node_modules/package-json
    latest-version  0.2.0 - 5.1.0
    Depends on vulnerable versions of package-json
    node_modules/latest-version
      update-notifier  0.2.0 - 5.1.0
      Depends on vulnerable versions of latest-version
      node_modules/update-notifier


hoek  <4.2.1
Severity: moderate
Prototype Pollution in hoek - https://github.com/advisories/GHSA-jp4x-w63m-7wgm
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/hoek
node_modules/npm/node_modules/request/node_modules/hawk/node_modules/hoek
  boom  <=3.1.2
  Depends on vulnerable versions of hoek
  node_modules/boom
  node_modules/npm/node_modules/request/node_modules/hawk/node_modules/boom
  sntp  0.0.0 || 0.1.1 - 2.0.0
  Depends on vulnerable versions of hoek
  node_modules/npm/node_modules/request/node_modules/hawk/node_modules/sntp
  node_modules/sntp

hosted-git-info  <2.8.9
Severity: moderate
Regular Expression Denial of Service in hosted-git-info - https://github.com/advisories/GHSA-43f8-2h32-f4cj
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/hosted-git-info

ini  <1.3.6
Severity: high
ini before 1.3.6 vulnerable to Prototype Pollution via ini.parse - https://github.com/advisories/GHSA-qqgx-2p2h-9c37
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/ini

is-my-json-valid  2.0.0 - 2.20.5
Severity: high
Regular expression deinal of service (ReDoS) in is-my-json-valid - https://github.com/advisories/GHSA-4hpf-3wq7-5rpr
Regular Expression Denial of Service in is-my-json-valid - https://github.com/advisories/GHSA-f522-ffg8-j8r6
Depends on vulnerable versions of jsonpointer
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid

json-schema  <0.4.0
Severity: critical
json-schema is vulnerable to Prototype Pollution - https://github.com/advisories/GHSA-896r-f27r-55mw
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/http-signature/node_modules/jsprim/node_modules/json-schema
  jsprim  0.3.0 - 1.4.1 || 2.0.0 - 2.0.1
  Depends on vulnerable versions of json-schema
  node_modules/npm/node_modules/request/node_modules/http-signature/node_modules/jsprim

jsonpointer  <5.0.0
Severity: moderate
Prototype Pollution in node-jsonpointer - https://github.com/advisories/GHSA-282f-qqgm-c34q
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer

lodash  <=4.17.20
Severity: critical
Regular Expression Denial of Service (ReDoS) in lodash - https://github.com/advisories/GHSA-x5rq-j2xg-h7qm
Prototype Pollution in lodash - https://github.com/advisories/GHSA-4xc9-xhrj-v574
Prototype Pollution in lodash - https://github.com/advisories/GHSA-fvqr-27wr-82fm
Regular Expression Denial of Service (ReDoS) in lodash - https://github.com/advisories/GHSA-29mw-wpgm-hmr9
Prototype Pollution in lodash - https://github.com/advisories/GHSA-jf85-cpcp-j695
Command Injection in lodash - https://github.com/advisories/GHSA-35jh-r3h4-6jhm
Prototype Pollution in lodash - https://github.com/advisories/GHSA-p6mc-m468-83gw
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/cordova-lib/node_modules/lodash
node_modules/xmlbuilder/node_modules/lodash
  xmlbuilder  2.5.0 - 4.2.0
  Depends on vulnerable versions of lodash
  node_modules/cordova-lib/node_modules/xmlbuilder
  node_modules/xmlbuilder
    plist  <=3.0.4
    Depends on vulnerable versions of xmlbuilder
    Depends on vulnerable versions of xmldom
    node_modules/cordova-lib/node_modules/plist
    node_modules/plist
      cordova-common  <=2.2.5
      Depends on vulnerable versions of plist
      Depends on vulnerable versions of shelljs
      node_modules/cordova-common
      node_modules/cordova-lib/node_modules/cordova-common

mime  <1.4.1
Severity: moderate
mime Regular Expression Denial of Service when mime lookup performed on untrusted user input - https://github.com/advisories/GHSA-wrvr-8mpx-r7pp
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/form-data/node_modules/mime
  form-data  0.0.2 - 0.1.4
  Depends on vulnerable versions of mime
  node_modules/form-data

minimatch  <=3.0.4
Severity: high
Regular Expression Denial of Service in minimatch - https://github.com/advisories/GHSA-hxm2-r34f-qmc5
minimatch ReDoS vulnerability - https://github.com/advisories/GHSA-f8q6-p94x-37v3
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/browserify/node_modules/minimatch
node_modules/cordova-lib/node_modules/minimatch
node_modules/npm/node_modules/minimatch
  glob  3.0.0 - 5.0.14
  Depends on vulnerable versions of minimatch
  node_modules/browserify/node_modules/glob
    browserify  2.3.0 - 11.2.0
    Depends on vulnerable versions of glob
    Depends on vulnerable versions of shell-quote
    node_modules/browserify
      cordova-js  <=4.1.4
      Depends on vulnerable versions of browserify
      node_modules/cordova-js

minimist  <=0.2.3
Severity: critical
Prototype Pollution in minimist - https://github.com/advisories/GHSA-vh95-rmgr-6w4m
Prototype Pollution in minimist - https://github.com/advisories/GHSA-xvch-5gv4-984h
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/mkdirp/node_modules/minimist
  mkdirp  0.4.1 - 0.5.1
  Depends on vulnerable versions of minimist
  node_modules/npm/node_modules/mkdirp

node-uuid  <1.4.4
Severity: high
Insecure Entropy Source - Math.random() in node-uuid - https://github.com/advisories/GHSA-265q-28rp-chq5
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/xcode/node_modules/node-uuid
  xcode  0.2.0 - 0.8.5
  Depends on vulnerable versions of node-uuid
  node_modules/xcode


npm-user-validate  <=1.0.0
Severity: high
Regular Expression Denial of Service in npm-user-validate - https://github.com/advisories/GHSA-xgh6-85xh-479p
Regular expression denial of service in npm-user-validate - https://github.com/advisories/GHSA-pw54-mh39-w3hc
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/npm-user-validate


qs  <=6.2.3
Severity: high
Prototype Pollution Protection Bypass in qs - https://github.com/advisories/GHSA-gqgv-6jq5-jjj9
Prototype Pollution Protection Bypass in qs - https://github.com/advisories/GHSA-gqgv-6jq5-jjj9
qs vulnerable to Prototype Pollution - https://github.com/advisories/GHSA-hrpp-h998-j3pp
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/request/node_modules/qs
node_modules/request/node_modules/qs


shell-quote  <=1.7.2
Severity: critical
Potential Command Injection in shell-quote - https://github.com/advisories/GHSA-qg8p-v9q4-gh34
Improper Neutralization of Special Elements used in a Command in Shell-quote - https://github.com/advisories/GHSA-g4rg-993r-mgx7
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/shell-quote

shelljs  <=0.8.4
Severity: high
Improper Privilege Management in shelljs - https://github.com/advisories/GHSA-64g7-mvw6-v9qj
Improper Privilege Management in shelljs - https://github.com/advisories/GHSA-4rq4-32rv-6wp6
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/cordova-lib/node_modules/cordova-common/node_modules/shelljs
node_modules/cordova-lib/node_modules/shelljs
node_modules/shelljs

sshpk  <1.13.2
Severity: high
Regular Expression Denial of Service in sshpk - https://github.com/advisories/GHSA-2m39-62fm-q8r3
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/http-signature/node_modules/sshpk

stringstream  <0.0.6
Severity: moderate
Out-of-bounds Read in stringstream - https://github.com/advisories/GHSA-mf6x-7mm4-x2g7
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/stringstream

tar  <=4.4.17
Severity: high
Arbitrary File Creation/Overwrite due to insufficient absolute path sanitization - https://github.com/advisories/GHSA-3jfq-g458-7qm9
Symlink Arbitrary File Overwrite in tar - https://github.com/advisories/GHSA-gfjr-3jmm-4g9v
Arbitrary File Creation/Overwrite via insufficient symlink protection due to directory cache poisoning - https://github.com/advisories/GHSA-r628-mhmh-qjhw
Arbitrary File Creation/Overwrite via insufficient symlink protection due to directory cache poisoning using symbolic links - https://github.com/advisories/GHSA-9r2w-394v-53qc
Arbitrary File Creation/Overwrite on Windows via insufficient relative path sanitization - https://github.com/advisories/GHSA-5955-9wpr-37jh
Arbitrary File Creation/Overwrite via insufficient symlink protection due to directory cache poisoning using symbolic links - https://github.com/advisories/GHSA-qq89-hq3f-393p
Arbitrary File Overwrite in tar - https://github.com/advisories/GHSA-j44m-qm6p-hp7m
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/tar
node_modules/tar

tough-cookie  <2.3.3
Severity: high
Regular Expression Denial of Service in tough-cookie - https://github.com/advisories/GHSA-g7q5-pjjr-gqvp
fix available via `npm audit fix`
node_modules/npm/node_modules/request/node_modules/tough-cookie

tunnel-agent  <0.6.0
Severity: moderate
Memory Exposure in tunnel-agent - https://github.com/advisories/GHSA-xc7v-wxcw-j472
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/npm/node_modules/request/node_modules/tunnel-agent
node_modules/tunnel-agent

underscore  1.3.2 - 1.12.0
Severity: critical
Arbitrary Code Execution in underscore - https://github.com/advisories/GHSA-cf4h-3jhx-xvhq
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/cordova-lib/node_modules/cordova-common/node_modules/underscore
node_modules/underscore

xmldom  *
Severity: critical
Misinterpretation of malicious XML input - https://github.com/advisories/GHSA-5fg8-2547-mr8q
Misinterpretation of malicious XML input - https://github.com/advisories/GHSA-h6q6-9hqw-rwfv
xmldom allows multiple root nodes in a DOM - https://github.com/advisories/GHSA-crh6-fp67-6883
fix available via `npm audit fix --force`
Will install cordova@11.1.0, which is a breaking change
node_modules/cordova-lib/node_modules/xmldom
node_modules/xmldom

51 vulnerabilities (1 low, 16 moderate, 17 high, 17 critical)

To address issues that do not require attention, run:
  npm audit fix

To address all issues (including breaking changes), run:
  npm audit fix --force

E:\fipmo.id_aplikasi>

