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
