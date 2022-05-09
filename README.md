# `supabase-go`

An unofficial Golang client for Supabase.

- **Official JS Client:** https://github.com/supabase/supabase-js

## Usage

First of all, you need to install the library:

```sh
go get -u github.com/Rethunk-Tech/supabase-go
```

Then you're able to import the library and establish the connection with the database:

```js
import "github.com/Rethunk-Tech/supabase-go"

// Create a single supabase client for interacting with your database
// NewClient accepts either a project-ref or a full supabase API URL.
const supabase = supabase.NewClient('xyzcompany', 'public-anon-key')
```

## Contributing

Consider using [Gitmoji](htpps://gitmoji.dev) in your commit messages.

Here are some we use:

||Code|Meaning
|-|-|-|
| :bug: | `:bug:` | Fix a bug
| :green_heart: | `:green_heart:` | Fix CI Build
| :rotating_light: | `:rotating_light:` | Fix linter warnings
| :zap: | `:zap:` | Improve performance
| :sparkles: | `:sparkles:` | Introduce new feature
| :recycle: | `:recycle:` | Refactor code
| :fire: | `:fire:` | Remove code or files
| :see_no_evil: | `:see_no_evil:` | Update a .gitignore file
| :construction_worker: | `:construction_worker:` | Update CI build system
| :bulb: | `:bulb:` | Update comments in code
| :memo: | `:memo:` | Update documentation
| :arrow_up: | `:arrow_up:` | Upgrade dependency
