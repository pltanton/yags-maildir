This is a plugin for [`YAGS`](https://github.com/pltanton/yags).

It displays number of new messages in maildir

# Configuration

| Key    | Description                         | Default value |
| ---    | ---                                 | ---           |
| dir    | path to maildir                     |               |
| empty  | format for 0 new messageds          | {new}         |
| filled | format for not empty new dirrectory | {new}         |

Available variables for interpolation:

| Variable name | Description                    |
| ---           | ---                            |
| new           | number of new mails in maildir |
