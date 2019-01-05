---
date: 2019-01-05T12:42:38Z
title: "filebrowser users new"
slug: filebrowser_users_new
url: /commands/filebrowser_users_new/
---
## filebrowser users new

Create a new user

### Synopsis

Create a new user and add it to the database.

```
filebrowser users new [flags]
```

### Options

```
      --commands strings    a list of the commands a user can execute
  -h, --help                help for new
      --locale string       locale for users (default "en")
      --lockPassword        lock password
  -p, --password string     new user's password
      --perm.admin          admin perm for users
      --perm.create         create perm for users (default true)
      --perm.delete         delete perm for users (default true)
      --perm.download       download perm for users (default true)
      --perm.execute        execute perm for users (default true)
      --perm.modify         modify perm for users (default true)
      --perm.rename         rename perm for users (default true)
      --perm.share          share perm for users (default true)
      --scope string        scope for users
      --sorting.asc         sorting by ascending order
      --sorting.by string   sorting mode (name, size or modified) (default "name")
  -u, --username string     new users's username
      --viewMode string     view mode for users (default "list")
```

### Options inherited from parent commands

```
  -d, --database string   path to the database (default "./filebrowser.db")
```

### SEE ALSO

* [filebrowser users](/commands/filebrowser_users/)	 - Users management utility

###### Auto generated by spf13/cobra on 5-Jan-2019