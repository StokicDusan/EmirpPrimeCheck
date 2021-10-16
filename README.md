[![Contributors][contributors-shield]][contributors-url]
[![Commit-activity][commit-activity-shield]][commit-activity-url]
[![Issues][issues-shield]][issues-url]
[![Repo-size][repo-size-shield]][repo-size-url]
[![License][license-shield]][license-url]  
[![Forks][forks-shield]][forks-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Welcome to EmirpPrimeCheck !!!

Script checks if the entered integer is an Emirp prime number or not.
An emirp is a prime number that results in a different prime when its decimal digits are reversed. 

## What does the script do?
The script prints a string informing whether or not the entered integer is an emirp prime number.

## `emirpPrimeCheck.py` :
This script is ready to use script which uses one arguments to run. The argument is the integer passed for the check.

## Installing the dependencies

### Used packages
This script require the math, sys and doctest package.

## How to use it
#### 1. Clone this repository:
```bash
$ git clone https://github.com/StokicDusan/EmirpPrimeCheck.git
$ cd EmirpPrimeCheck/
```
#### 2. Launch:
In the command line simply invoke the script with one argument:
```bash
$ python emirpPrimeCheck.py argv1
```
* argv1:  
Any positive integer  

:warning: *Note:* Other input will result in an error

Invoking the script with no or less arguments will run testmod().

## Examples

The following code block shows examples of calling the emirpPrimeCheck script from terminal.

```bash
$ python3 emirpPrimeCheck.py 100
It is not an Emirp
$ python3 emirpPrimeCheck.py 311
It is an Emirp!
$ python3 emirpPrimeCheck.py 12721
It is not an Emirp, palindromes don't count
```

## Provide Feedback 👍

If you encounter any bugs or have suggestions, please file an issue in the
[Issues][issues-url]
section of the project.

[contributors-shield]: https://img.shields.io/github/contributors/StokicDusan/EmirpPrimeCheck
[contributors-url]: https://github.com/StokicDusan/EmirpPrimeCheck/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/StokicDusan/EmirpPrimeCheck?style=social
[forks-url]: https://github.com/StokicDusan/EmirpPrimeCheck/network/members
[issues-shield]: https://img.shields.io/github/issues/StokicDusan/EmirpPrimeCheck
[issues-url]: https://github.com/StokicDusan/EmirpPrimeCheck/issues
[commit-activity-shield]: https://img.shields.io/github/last-commit/StokicDusan/EmirpPrimeCheck
[commit-activity-url]: https://github.com/StokicDusan/EmirpPrimeCheck/graphs/commit-activity
[license-url]: https://github.com/StokicDusan/EmirpPrimeCheck/blob/main/LICENSE
[license-shield]: https://img.shields.io/github/license/StokicDusan/EmirpPrimeCheck
[repo-size-shield]: https://img.shields.io/github/repo-size/StokicDusan/EmirpPrimeCheck
[repo-size-url]: https://img.shields.io/github/repo-size/StokicDusan/EmirpPrimeCheck
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=plastice&logo=linkedin&logoColor=white
[linkedin-url]: https://linkedin.com/in/stokicdusan
