# Hackforces


| Challenge                  |          |                                                |
|----------------------------|----------|------------------------------------------------|
| uid                        | string   | "not null, primary key"                        |
| name                       | string   | not null                                       |
| description                | string   |                                                |
| author/source              | string   |                                                |
| link download/ storage.zip | ???      |                                                |
| createdAt                  | datetime | not null                                       |
| tag                        | string   | not null                                       |
| flag                       | string   | not null                                       |
| point/level                | int      | not null                                       |

<br>

| User                       |          |                                                |
|----------------------------|----------|------------------------------------------------|
| uid                        | string   | "not null, primary key"                        |
| username/email             | string   | not null                                       |
| password                   | string   | not null                                       |
| university                 | string   |                                                |
| createdAt                  | datetime | not null                                       |
| Avatar                     | ???      |                                                |
| Description                | string   |                                                |

<br>


| Solved                     |          |                                                |
|----------------------------|----------|------------------------------------------------|
| chall_uid                  | string   | "not null, foreign key reference to Challenge" |
| usr_uid                    | string   | "not null, foreign key reference to User"      |
| solvedAt                   | datetime | not null                                       |


