# molecule-ec2-boilerplate configuration

## Description
This is a boilerplate configuration to run unit tests on ansible roles with molecule via AWS EC2 Instances. As I could not find clear and concise documentation (that provided working examples) on how to use the plugin, I put together my own working example and created this boilerplate.

## Installation
1. Clone this repository to your local workstation.
2. Move the molecule folder into your ansible role working directory.
3. Run `pip install ansible molecule molecule-plugins boto3 botocore`.

## Usage
Run `molecule test`.

## Contributing
Open an issue or submit a pull request with the fix.

## License
MIT

## Contact
Contact via GitHub issues page.