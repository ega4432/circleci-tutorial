# circleci-tutorial
## branch
| name | status | document |
| :---: | :---: | :---: |
| master | [![yoshimitsuEgashira](https://circleci.com/gh/yoshimitsuEgashira/circleci-tutorial.svg?style=shield)](https://circleci.com/gh/yoshimitsuEgashira/circleci-tutorial) | [Hello World](https://circleci.com/docs/ja/2.0/hello-world/) |
| php | [![yoshimitsuEgashira](https://circleci.com/gh/yoshimitsuEgashira/circleci-tutorial/tree/php.svg?style=shield)](https://circleci.com/gh/yoshimitsuEgashira/circleci-tutorial/tree/php) | [言語ガイド：PHP](https://circleci.com/docs/ja/2.0/language-php/) |
| go | will implement | |
| ... |  | |

## status badge styles
[document](https://circleci.com/docs/2.0/status-badges/)
- style=svg
    - [![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://circleci.com/gh/circleci/circleci-docs)
- style=shield
    - [![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=shield)](https://circleci.com/gh/circleci/circleci-docs)

## Local CLI
- Install
    -  ver macOS

```bash
$ curl -fLSs https://circle.ci/cli | bash`
```

- Update / Setup

```bash
$ circleci update

$ circleci setup
# Create your API token from `https://circleci.com/account/api`
```

- Sytax check

```bash
# Make sure `.circleci/config.yml` exists in the current directory
$ circleci config validate
```

- Excute job

```bash
$ circleci local execute --job JOB_NAME
```
