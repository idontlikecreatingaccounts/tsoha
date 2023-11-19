Table users {
    id integer [primary key]
    username varchar
    password varchar
    email varchar
    joindate timestamp
}

Table messages {
    id integer [primary key]
    user_id integer
    thread_id integer
    title varchar
    message varchar
}

Table threads {
    id integer [primary key]
    title varchar
    user_id integer
    area_id integer
}

Table areas {
    id integer [primary key]
    name varchar
    visibility integer
}


Ref: messages.user_id > users.id
Ref: messages.thread_id > threads.id

Ref: threads.user_id > users.id
Ref: threads.area_id > areas.id


