icecp-module-template
=====================

This repository provides a parent POM for quicker module development. It provides common properties, profiles, dependencies, etc., that the team has found useful while developing modules. 

### Install

1. Run `mvn install`

### Use

Insert the following in the module that will use this module's properties:

```
<parent>
    <groupId>com.intel.icecp</groupId>
    <artifactId>icecp-module-template</artifactId>
    <version>LATEST</version>
</parent>
```

`LATEST` will ensure the latest template is retrieved which means any updates to the template will be reflected in the descending modules; if these updates are undesired, the specific POM version should be used, e.g. `0.1.0`


### License

Copyright &copy; 2016, Intel Corporation 

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
