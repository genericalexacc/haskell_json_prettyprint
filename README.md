# JSON Pretty Printer in Haskell

A JSON prettyprinter I wrote while learning Haskell.

```console
foo@bar:~$ runghc Setup configure
foo@bar:~$ runghc Setup build
foo@bar:~$ runghc Setup install

Then in GHCI

foo@bar:~$ Prelude> let value = renderJValue (JObject [("f", JNumber 1), ("q", JBool True)])
foo@bar:~$ Prelude> putStrLn (pretty 30 value)
{"f": 1.0, "q": true }

```

