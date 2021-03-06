# GetChef

Personal script to install Chef Client from package repositories.

## Prerequisites

* You must install `git` first on the node on which you want to install
Chef tooling to use this repository.
* Currently only Debian distributions are supported.

## Usage

After satisfying the prerequisites, do the following to install the
latest nightly release of Chef DK:

* First, clone this repository from
your shell and set its root as your shell's current directory:

```sh
git clone https://github.com/adamedx/getchef
cd getchef
```

* The use any of the following commands to install Chef DK from within the repository:

```sh
sudo ./getchefdk.sh # If you want the latest nightly build
sudo ./getchefdk-stable.sh # For the latest stable build

```

### Installing only Chef Client
Similar to the commands above, you may use the following scripts to
install just Chef Client (which is included in Chef DK):

```sh
sudo ./getchef.sh
```

or

```sh
sudo ./getchef-stable.sh

```

License and Authors
-------------------
Copyright:: Copyright (c) 2015 Adam Edwards

License:: Apache License, Version 2.0

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


