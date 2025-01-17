#### 1.5.0: Release

 - Add NR 3.1.0 build (#120) @hardillb
 - Add support to supply Private ca certificate bundle (#117) @hardillb
 - Allow empty SMTP user/pass (#116) @hardillb

#### 1.4.0: Release

 - Remove hard coded ingress annotations for AWS (#113) @hardillb
 - Add eslint for test files (#111) @knolleary
 - Add device product/price to config map (#110) @knolleary
 - Fix line break in telemetry (#109) @hardillb
 - Add posthog apihost to config (#107) @hardillb
 - Fix missing `s` in default context host (#105) @hardillb
 - Add more tests (#103) @hardillb
 - First pass at basic tests for Helm Chart (#90) @hardillb
 - Wait for containers to build before publish helm (#101) @hardillb
 - Fix Go Template formating for frontend telemetry (#102) @hardillb

#### 1.3.0: Release

 - Add branding inserts (#99) @hardillb
 - Add support for Free trial configuration (#96) @hardillb
 - Bump 2.2.3 container to NodeJS 16 base (#97) @hardillb
 - Add support for HubSpot support agent (#95) @hardillb
 - Add deployment permissions (#93) @hardillb
 - Allow upgrade DB script to run without failing (#92) @hardillb
 - Fix configmap (#89) @flecoufle
 - Fix gha (#86) @hardillb
 - Fix helm chart publish (#85) @hardillb

#### 1.2.0: Release

 - Add context store provisioning (#79) @hardillb
 - Add enabled flags for broker and file-server (#73) @hardillb
 - Expose the port so it can be used for HTTP-in/out (#82) @hardillb
 - No need to symlink python3 anymore (#81) @hardillb
 - Docker: Publish images for the device agent (#80) @ZJvandeWeg
 - Publish helm (#78) @hardillb

#### 1.1.0: Release

 - Fix indentation in file-server.yml (#67) @hardillb
 - Rename file-storage package (#66) @hardillb
 - Add File Server (#64) @hardillb
 - Update helm chart readme about node selectors (#65) @hardillb
 - Typo in docs for ProjectSelector (#63) @hardillb
 - Fix path to README (#62) @hardillb

#### 1.0.1: Release

 - Update for FlowForge 1.0.1
 
#### 1.0.0: Release

 - Remove flowforge nodes from /data/package.json (#56) @hardillb
 - Push README.md files to Docker Hub with each release (#54) @hardillb
 - Limiting the containers capabilities (#53) @hardillb
 - Allow EE license to be added to configmap from helm chart (#45) @hardillb

#### 0.10.0: Release

 - Fix case on npm authToken (#46) @hardillb
 - Use GH token to auth if using custom repo (#44) @hardillb
 - Move to docker GH actions (#43) @hardillb

#### 0.9.0: Release

- containers: Publish containers publicly each release @ZJvandeWeg
 - Add option to overide forge app container image (#39) @hardillb
 - Set correct default broker url (#38) @hardillb
 - Add team types (#37) @hardillb
 - Add support for PostHog metrics (#36) @hardillb
 - Versioning (#34) @hardillb
 - Add Health Check URL for MQTT broker (#35) @hardillb
#### 0.8.0: Release

 - Bump version for 0.8.0 (#32) @hardillb
 - Update auth http paths (#31) @hardillb
 - Add plausible config (#30) @hardillb
 - add dep @flowforge/nr-project-nodes (#29) @Steve-Mcl
 - Start of adding the broker (#26) @hardillb
 - Add FF Theme to node-red container (#25) @hardillb

#### 0.7.0: Release

 - Fix missing Python2 for sqlite3 (#23) @hardillb

#### 0.6.0: Release


#### 0.5.0: Release

#### 0.4.0: Release

 - Update project automation (#17) @knolleary
 - Fix version of NR available to Launcher (#16) @hardillb
 - Add billing template to helm config (#15) @hardillb
 - Update README.md (#14) @hardillb
 - Allow Project Node selector to be set (#13) @hardillb
 - Only apply ALB annotation on AWS (#12) @hardillb

#### 0.3.0: Release

 - Fix when not running on AWS (#10) @hardillb
 - Add to node-red container as well (#9) @hardillb
 - Add option to specify npm registry (#8) @hardillb

#### 0.2.0: Release

 - Add default host config to 0.0.0.0 (#7) @hardillb
 - First AWS EKS deployment (#5) @hardillb
 - Add more email config (#4) @hardillb
 - Add ALB annotations (#3) @hardillb
 - Add project workflow automation (#2) @knolleary
 - Make installing Postgres optional (#1) @hardillb

 
