# Prisma Cloud IaC scanner

## Usage

Use one of `0_high_alert.template` or `1_high_alert.template` to demonstrate IaC scanner.
They are both AWS Cloud formation configuration, and only `1_high_alert.template` include one high compliance alert.
By commenting out 11th(0_high_alert.templat) or ether 12th (1_high_alert.templat) in .circleci/config.yml to switch code to be scanned.
`1_high_alert.template` should return alert "AWS RDS instance is not encrypted".
