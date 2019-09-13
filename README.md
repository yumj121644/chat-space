| body | text | null: false |
| image | string | |
| group | references | foreign_key: true |
| user | references | foreign_key: true |


**Association**
* belongs_to :user
| Column | type | Option |
|:--|:--|:--|
| group | references | index: true, foreign_key: true, null: false |
| user | references | index: true, foreign_key: true, null: false |


**Association**
* belongs_to :group
* belongs_to :user
***
