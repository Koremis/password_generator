# password_generator
CLI tool that outputs secure random passwords

CLI tool that outputs secure random passwords of a given length. You can also specify what special characters are used.
## Options

      -l or --length - integer to determine length of password
          defaults to 12 characters
      -s or --special_characters - string of characters that can be used
          defaults to !@#$%^&*
          note: specify string using ' ' as in 'special characters here' to avoid escapes
## Example

      $ password_generator -l 24 -s '!@#$%^&*()_+-=,.<>/?'

      $ outputs_random_password
