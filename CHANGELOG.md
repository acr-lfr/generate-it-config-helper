## 1.4.1 - 2022-05-18

- FEAT: withDefault and required now also sets a new var under `CONFIG_HELPER_` prefix: `process.env['CONFIG_HELPER_' + environmentVariable]`

# 1.3.1 and below - 2020-07-21

- FEAT: required will throw an error if the var was not found in the process.env object
- FEAT: withDefault will return a default value provided if not found in the process.env object
