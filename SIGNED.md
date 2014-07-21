##### Signed by https://keybase.io/shrikeh
```
-----BEGIN PGP SIGNATURE-----
Version: GnuPG v1

iQIcBAABAgAGBQJTzQdiAAoJEE4AEBkkrX9/g+sP/2TB86n9nTLahzErkrJvLLg8
3q6XBBWSa+BXsSy6C6j+1yWjw06XIIkD8RYzzu0eB0S7Jgb63OlpxoqFB5LpIvYF
ytDnPPqfVpWK4qvP7eIvUhJrBeGsCm+A6Pvn98TxNmZpJ1KquJwTYGqtUhWBJ6Bc
ZUaFft9zuT/qT3UXKuRQvHzK9jQWnes0j46NuPiRFGLbHdsa06p2t6lOiOWy5A9Y
Ig51t7+j6GhB5tRHaklgE7cf41Ftg/mhTtbMlcpUVOd/RFufB2G8FWgbGDuJvMFH
i0UF9gqaEG1rSXqlxAYFlpDta9l9ua5w6jtNFMorwaYlvKmPR3c01NsqDAM+8scK
tPOU1CHNkot69IeDGVrwrqdbvgBomeeToqdzyGFhI9LMJoD2+C+eoHGKnSnsXLGt
HTvZwkxadDch6KCJ4tja3fce73pDZdsmoURoWVClIQkdeNNevXFmW8UhgkbmYZVG
b5Mpw1f1EFDnTZyeNVtVq7S50sZRf02+abfuOWal9YmYCJKXxurLgUkPRNawrgwW
LWioimGSB/cD8BUD6rRcNUEtA/hm+zsdZH/HUCTfdTnkc9RgWpUYbOKR17KFWwHJ
DTgAn9EzoMx/mYVVhkIdirx3HSWeOf5Vq6FlZDz/NZV26girfJXFnSxCRa+bDTue
N82gyEWCd1sLSOpUbU7X
=oSYv
-----END PGP SIGNATURE-----

```

<!-- END SIGNATURES -->

### Begin signed statement 

#### Expect

```
size   exec  file                    contents                                                        
             ./                                                                                      
11             .gitignore            e02f70856647881c22afcee6359eacfc719eacd187de560878d75420ff015ed8
8              README.md             96a4cc553879f5d9d721b03304d8283720e1ad77d747f249fbf2a50667f76aee
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