##### Signed by https://keybase.io/shrikeh
```
-----BEGIN PGP SIGNATURE-----
Version: GnuPG v1

iQIcBAABAgAGBQJTzRRYAAoJEE4AEBkkrX9/njYP/iujfeXrNcPR16hYgj9opfh4
rzg2llq4AjcbliKBJKhAHaBBrmW3RuepKFy99H0FpbPN+huUgWe3h+mbluidQMBF
c/N0y6SVrDo6sgNd5MaceJ+/7TDoIblKi6sQyBnkP4CJn1gZjc1/iuMr44/38dXE
qu/xaM6lPNDVNCyzYPFgKyjxqBiLqrBqViTrGQ8Hm7I+UEl4T5ImDtw7PoHvLUGp
EmWfxA4sr+65twEEX8cK/5ySP5XLsx8KKMHL+VNZThBr9lPC2DyNUr3ChggbiPnQ
j2UVu+LnLhC/rXNSEnUd2QI1/gE7TBK2f2zrJxjvHpeGTEG8SigtKsU6HX9Mo4E3
3ASHKtNxX4/y5nnMaTTNN/Idp4OEDRY+F/a5T4gX27gEFfthAMcw8dObrZvakqc/
kaBdM+9IcSHxs+0qHrvduowVlqcKw2WIf39595ZqDyUhIbtLBUS4CES9T5v8Lckl
zeiv3XpoUnc1ftPTaptwDZwvy8Qr9NBo9KFTTJ2Wn7h8F1bvb+58iEu6jItKbRYk
rxcWruR2X9Ci7B0N4xbdoRej5dZY1ziRqWslmtjpncxBhdtE795ZfV1l0JjJ1O+n
BPWJoAEGl9aj+VUYNKHFj8MoTOAMXf/4wo8WXLrkRj0+jcDbU2ETm+z37ofwzzRA
pAbVa2rLNs6Y7S1oVm/c
=s8An
-----END PGP SIGNATURE-----

```

<!-- END SIGNATURES -->

### Begin signed statement 

#### Expect

```
size   exec  file                    contents                                                        
             ./                                                                                      
11             .gitignore            e02f70856647881c22afcee6359eacfc719eacd187de560878d75420ff015ed8
75             .travis.yml           d130abd108337253f2b8424fb736b1567e5ce0ec04d3b27120442a7cd3984d35
29             README.md             baaee3d807c069c441fe7b3206a1ef8733fe2f8dd15054f7a210e5f6a66961f2
1086           apiary.apib           6581521b544f74a58774a2e15c68182650c1ed6ffa9f46b1b6d4dd64a72a0328
221            behat.yml             b9d5f0d79f423f305e12fd1d3d3a6bd4241550e3c62a58ccc73d872f8256376c
572            composer.json         c5dd18b81d3bed542e24b84e068db60c4686d7a82e007df2b1fd45dd2b3c8ea9
31309          composer.lock         30a479e008d02aced854c2e7900f6462101259d083185e043fe7ea5081f6215f
117            phpspec.yml           a86248d6cf15d458888361aa5dce8d96d3ead2d1b0e86138aaf6715a9cbd1d2d
               test/                                                                                 
                 features/                                                                           
                   bootstrap/                                                                        
455                  ApiContext.php  be8ef2eee54219a5145eb5cb7c425df65ec0c75800f3bd1cd4e486de147a50e4
                 specs/                                                                              
```

#### Ignore

```
/SIGNED.md
```

#### Presets

```
git      # ignore .git and anything as described by .gitignore files
dropbox  # ignore .dropbox-cache and other Dropbox-related files    
kb       # ignore anything as described by .kbignore files          
```

<!-- summarize version = 0.0.9 -->

### End signed statement

<hr>

#### Notes

With keybase you can sign any directory's contents, whether it's a git repo,
source code distribution, or a personal documents folder. It aims to replace the drudgery of:

  1. comparing a zipped file to a detached statement
  2. downloading a public key
  3. confirming it is in fact the author's by reviewing public statements they've made, using it

All in one simple command:

```bash
keybase dir verify
```

There are lots of options, including assertions for automating your checks.

For more info, check out https://keybase.io/docs/command_line/code_signing