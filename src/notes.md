# Notes
## Repl
### Basic commands
```bash
$ ghci          # Start the repl
Prelude>  :q    # Quit the repl
Prelude>  :?    # List all commands
Prelude>  :i    # (:i alias for :info) Get informations about a type. Ex: :info Num
Prelude>  :t    # (:t alias for :type) Get the type of a value. Ex: :type 23 
```

### Using a module
```bash
Prelude> :l src/MyFile.hs   # (:l alias for :load) Load the module file
MyFile> :r                 # (:r alias for :reload) reload the module (no need to specify the name)
```

### Mutli line instructions
```bash
Prelude> :{ # Starts a multi line block
Prelude| squareSum :: Int -> Int -> Int
Prelude| squareSum x y = (x + y) * (x + y)
Prelude| :} # Ends a multi line block
Prelude> squareSum 2 2
16
```



## Commands

```bash
```
```bash
```
```bash
```
```bash
```
```bash
```
```bash
```
