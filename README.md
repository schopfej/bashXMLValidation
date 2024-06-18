# bashXmlValidation

## Overview

This Bash script checks whether the ID of `.zip` and `.xml` files in a specified source directory match and validates that the `.xml` files inside the `.zip` files meet certain conditions. 
It then optionally moves these files to a target directory. The script also supports a test mode where it performs checks but does not move files.

## Usage

```bash
./validate_and_set.sh [-h] [-T] <directory_path_1> <directory_path_2>
