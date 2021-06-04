# テーブル設計

## users テーブル

| Column             | Type   | Options     |
| ------------------ | ------ | ----------- |
| name               | string | not: null   |
| email              | string | not: null   |
| password           | string | not: null   |
| profile            | text   | not: null   |
| occupation         | text   | not: null   |
| position           | text   | not: null   |


## prototypes テーブル

| title      | string     | not: null |
| catch copy | text       | not: null |
| concept    | text       |           |
| image      |            |           |
| user       | references |           |

## comments テーブル

| text      | text       | not: null |
| user      | references |           |
| prototype | references |           |



