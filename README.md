# Homebrew Tap - Terragrunt Version Manager

Homebrew tap for the Terragrunt version manager (tgenv) formula.

## How do I install this formula?

First `brew tap project-hamilton/tgenv`.  This will setup the tap to access the formula in this repository.

If you already have Terragrunt installed via Homebrew, then you need to unlink the existing install as it will conflict with tgenv, `brew unlink terragrunt`.

Then `brew install tgenv`.

## How do I install terragrunt after I install the formula?

For the latest Terragrunt release, `tgenv install latest`.

For a specific Terragrunt release, `tgenv install 0.18.6` (replace "0.18.6" with whatever release you're aiming for).

See our [tgenv repo](https://github.com/project-hamilton/tgenv) for additional information on the use of tgenv.
