# DNACRYPTKEY

DNACRYPTOKEY is a package to use in python that uses DNA code-based encryption to hide messages.

## Getting Started

Just use pip to install it! 

### Prerequisites

To use dnacryptkey is necessary have installed random package and unidecode package.

```
pip install random
pip install unidecode
```

### Installing

Check that the packages random and unidecode have been installed

Use this command in terminal to verify it:

```
pip freeze
```

*If necessery install packages random and unidecode!

And install DNACRYPTKEY using this command in terminal:

```
pip install dnacryptkey
```

If you want, install dnacryptkey and use command status() to verify status of package.

## Running the test


dnacryptkey uses third-party packages to run.


### Test status dnacryptkey

```
import dnacryptkey
print(dnacryptkey.dnacryptkey.required)
print(dnacryptkey.dnacryptkey.status())
```

### See how to use it

```
import dnacryptkey 
print(dnacryptkey.dnacryptkey.use)
```

### See description

```
import dnacryptkey
print(dnacryptkey.dnacryptkey.description)
```


### How to use it

## To encrypt the message use this command:

```
dnacryptkey.dnacryptkey('encrypt','Esse script foi feito pensando melhorar minhas skills','chavesecreta')
```

## Output

UUUUUCUUAUUGUCUUCCUCAUCGUAUUACGCAUGUUGCGCGUGGCUUCUCCUACUGCCUCCCCCACCGCAUCACCAACAGCGUCGCCGAAUGUCUAGAAGACGGGAUAGACGCAGCACUAAGAGGGAUAUUAAAACUGAUAUUCGGACUAGGAAAGAUAAGCGGAACAGACAGAACCGAAAAGAUAAUCGGACGAUAAAAAGCCAGAGCGAUAAUACUAACAUACAGAGAGAUAGAACAACUACGACGAGAUAAUUUUUCUUAUUGUCUUCCUCAUCGUAUUACGCAUGUUGCGCGUGGCUUCUCCUACUGCCUCCCCCACCGCAU

## To decrypt the message use this command:

```
dnacryptkey.dnacryptkey('decrypt','UUUUUCUUAUUGUCUUCCUCAUCGUAUUACGCAUGUUGCGCGUGGCUUCUCCUACUGCCUCCCCCACCGCAUCACCAACAGCGUCGCCGAAUGUCUAGAAGACGGGAUAGACGCAGCACUAAGAGGGAUAUUAAAACUGAUAUUCGGACUAGGAAAGAUAAGCGGAACAGACAGAACCGAAAAGAUAAUCGGACGAUAAAAAGCCAGAGCGAUAAUACUAACAUACAGAGAGAUAGAACAACUACGACGAGAUAAUUUUUCUUAUUGUCUUCCUCAUCGUAUUACGCAUGUUGCGCGUGGCUUCUCCUACUGCCUCCCCCACCGCAU','chavesecreta')
```

## Output

Esse script foi feito pensando melhorar minhas skills.

## Built With

* [VisualCode](Esse script foi feito pensando melhorar minhas skills) - The web framework used
* [CataLux](https://catalux.com.br/) - CataLux Labs


## Authors

* **Rodrigo Forti** - *Initial work* - [CataLux Python Labs](https://github.com/FortiHub)

See also the list of [contributors](https://github.com/catalux/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* This code was created to improve learning skills.
* Enjoy your self!
