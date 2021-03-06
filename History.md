# 1.0.1 / 2017-04-21

  * Fix: Update vendored libraries

# 1.0.0 / 2017-04-21

This version introduces a breaking change: The vault keys are no longer provided as arguments to the command but as parameters. Also this introduces the potential to supply multiple vault keys. Their contents will be combined and supplied as environment variables to the executed command or the export statements.

  * Breaking: Move vault keys to parameters
  * Breaking: Remove deprecated AppID authentication
  * Fix: Missing parameter in README

# 0.6.1 / 2016-11-21

  * Add github publishing

# 0.6.0 / 2016-10-04

  * Add transform feature to rename keys from Vault

# 0.5.0 / 2016-09-18

  * Add support for AppRole authentication

# 0.4.2 / 2016-06-25

  * Fix: Added godeps

# 0.4.1 / 2016-06-25

  * Fix: Updated godeps

# 0.4.0 / 2016-06-25

  * If not specified use token from ~/.vault-token

# 0.3.1 / 2016-05-29

  * Fix: Remove program name from program args

# 0.3.0 / 2016-05-29

  * Enable token auth

# 0.2.0 / 2016-05-29

  * Added command execution in addition to execution

# 0.1.1 / 2016-05-29

  * Fix: README looked wrong

# 0.1.0 / 2016-05-29

  * First version