# habits

## Description

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | int |  | false |  |  |  |
| name | varchar(50) |  | false |  |  |  |
| description | varchar(150) |  | false |  |  |  |
| contact_id | int |  | false |  |  |  |
| per_week | int |  | false |  |  |  |
| per_month | int |  | false |  |  |  |
| per_year | int |  | false |  |  |  |
| status | bit | ((1)) | false |  |  |  |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| PK__habits_* | PRIMARY KEY | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ id ] |

## Indexes

| Name | Definition |
| ---- | ---------- |
| PK__habits_* | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ id ] |

## Relations

![er](habits.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
