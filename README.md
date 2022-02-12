# NeuVector

NeuVector vulnerability scanner for the SUSE NeuVector Container Security Platform.

A viewable version of docs can be seen at https://open-docs.neuvector.com.

The container images for the preview version can be pulled from the NeuVector Docker Hub registry at:
+ neuvector/manager.preview:5.0.0-preview.1
+ neuvector/controller.preview:5.0.0-preview.1
+ neuvector/enforcer.preview:5.0.0-preview.1
+ neuvector/scanner.preview:latest
+ neuvector/updater.preview:latest

If deploying with the current NeuVector Helm chart (v1.8.9+), the following changes should be made to values.yml:

+ Update the registry to docker.io
+ Update image names/tags to the preview version on Docker hub, as shown above
+ Leave the imagePullSecrets empty

# Bugs & Issues
Please submit bugs and issues to [neuvector/neuvector](//github.com/neuvector/neuvector/issues) with a title starting with `[SCAN] `.

Or just [click here](//github.com/neuvector/neuvector/issues/new?title=%5BSCAN%5D%20) to create a new issue.

# License

Copyright © 2016-2022 [NeuVector Inc](https://neuvector.com). All Rights Reserved

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
