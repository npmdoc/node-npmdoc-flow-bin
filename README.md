# api documentation for  [flow-bin (v0.43.0)](https://github.com/flowtype/flow-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-flow-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-flow-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-flow-bin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-flow-bin)
#### Binary wrapper for Flow - A static type checker for JavaScript

[![NPM](https://nodei.co/npm/flow-bin.png?downloads=true)](https://www.npmjs.com/package/flow-bin)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flow-bin/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-flow-bin_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flow-bin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-flow-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-flow-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "email": "sindresorhus@gmail.com",
        "url": "sindresorhus.com"
    },
    "bin": {
        "flow": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/flowtype/flow-bin/issues"
    },
    "dependencies": {},
    "description": "Binary wrapper for Flow - A static type checker for JavaScript",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5cd16696be4311c0b14f0932e89ba8661a39b1c1",
        "tarball": "https://registry.npmjs.org/flow-bin/-/flow-bin-0.43.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "flow-linux64-v*/flow",
        "flow-osx-v*/flow",
        "flow-win64-v*/flow.exe",
        "vendor",
        "cli.js",
        "index.js",
        "SHASUM256.txt"
    ],
    "gitHead": "8d5a940fcf1726536df835119b91cae29d15a8aa",
    "homepage": "https://github.com/flowtype/flow-bin#readme",
    "keywords": [
        "cli-app",
        "cli",
        "bin",
        "binary",
        "flow",
        "facebook",
        "type",
        "inference",
        "check",
        "checker",
        "javascript",
        "js",
        "wrapper"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "gabelevi",
            "email": "gabelevi@gmail.com"
        },
        {
            "name": "jeffmo",
            "email": "lbljeffmo@gmail.com"
        },
        {
            "name": "kevva",
            "email": "kevinmartensson@gmail.com"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        }
    ],
    "name": "flow-bin",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/flowtype/flow-bin.git"
    },
    "scripts": {
        "test": "echo \"Error: Run 'make test' instead.\" && exit 1",
        "verify": "shasum -c SHASUM256.txt"
    },
    "version": "0.43.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module flow-bin](#apidoc.module.flow-bin)
1.  string <span class="apidocSignatureSpan">flow-bin.</span>0
1.  string <span class="apidocSignatureSpan">flow-bin.</span>1
1.  string <span class="apidocSignatureSpan">flow-bin.</span>10
1.  string <span class="apidocSignatureSpan">flow-bin.</span>11
1.  string <span class="apidocSignatureSpan">flow-bin.</span>12
1.  string <span class="apidocSignatureSpan">flow-bin.</span>13
1.  string <span class="apidocSignatureSpan">flow-bin.</span>14
1.  string <span class="apidocSignatureSpan">flow-bin.</span>15
1.  string <span class="apidocSignatureSpan">flow-bin.</span>16
1.  string <span class="apidocSignatureSpan">flow-bin.</span>17
1.  string <span class="apidocSignatureSpan">flow-bin.</span>18
1.  string <span class="apidocSignatureSpan">flow-bin.</span>19
1.  string <span class="apidocSignatureSpan">flow-bin.</span>2
1.  string <span class="apidocSignatureSpan">flow-bin.</span>20
1.  string <span class="apidocSignatureSpan">flow-bin.</span>21
1.  string <span class="apidocSignatureSpan">flow-bin.</span>22
1.  string <span class="apidocSignatureSpan">flow-bin.</span>23
1.  string <span class="apidocSignatureSpan">flow-bin.</span>24
1.  string <span class="apidocSignatureSpan">flow-bin.</span>25
1.  string <span class="apidocSignatureSpan">flow-bin.</span>26
1.  string <span class="apidocSignatureSpan">flow-bin.</span>27
1.  string <span class="apidocSignatureSpan">flow-bin.</span>28
1.  string <span class="apidocSignatureSpan">flow-bin.</span>29
1.  string <span class="apidocSignatureSpan">flow-bin.</span>3
1.  string <span class="apidocSignatureSpan">flow-bin.</span>30
1.  string <span class="apidocSignatureSpan">flow-bin.</span>31
1.  string <span class="apidocSignatureSpan">flow-bin.</span>32
1.  string <span class="apidocSignatureSpan">flow-bin.</span>33
1.  string <span class="apidocSignatureSpan">flow-bin.</span>34
1.  string <span class="apidocSignatureSpan">flow-bin.</span>35
1.  string <span class="apidocSignatureSpan">flow-bin.</span>36
1.  string <span class="apidocSignatureSpan">flow-bin.</span>37
1.  string <span class="apidocSignatureSpan">flow-bin.</span>38
1.  string <span class="apidocSignatureSpan">flow-bin.</span>39
1.  string <span class="apidocSignatureSpan">flow-bin.</span>4
1.  string <span class="apidocSignatureSpan">flow-bin.</span>40
1.  string <span class="apidocSignatureSpan">flow-bin.</span>41
1.  string <span class="apidocSignatureSpan">flow-bin.</span>42
1.  string <span class="apidocSignatureSpan">flow-bin.</span>43
1.  string <span class="apidocSignatureSpan">flow-bin.</span>44
1.  string <span class="apidocSignatureSpan">flow-bin.</span>45
1.  string <span class="apidocSignatureSpan">flow-bin.</span>46
1.  string <span class="apidocSignatureSpan">flow-bin.</span>47
1.  string <span class="apidocSignatureSpan">flow-bin.</span>48
1.  string <span class="apidocSignatureSpan">flow-bin.</span>49
1.  string <span class="apidocSignatureSpan">flow-bin.</span>5
1.  string <span class="apidocSignatureSpan">flow-bin.</span>50
1.  string <span class="apidocSignatureSpan">flow-bin.</span>51
1.  string <span class="apidocSignatureSpan">flow-bin.</span>52
1.  string <span class="apidocSignatureSpan">flow-bin.</span>53
1.  string <span class="apidocSignatureSpan">flow-bin.</span>54
1.  string <span class="apidocSignatureSpan">flow-bin.</span>55
1.  string <span class="apidocSignatureSpan">flow-bin.</span>56
1.  string <span class="apidocSignatureSpan">flow-bin.</span>57
1.  string <span class="apidocSignatureSpan">flow-bin.</span>58
1.  string <span class="apidocSignatureSpan">flow-bin.</span>59
1.  string <span class="apidocSignatureSpan">flow-bin.</span>6
1.  string <span class="apidocSignatureSpan">flow-bin.</span>60
1.  string <span class="apidocSignatureSpan">flow-bin.</span>61
1.  string <span class="apidocSignatureSpan">flow-bin.</span>62
1.  string <span class="apidocSignatureSpan">flow-bin.</span>63
1.  string <span class="apidocSignatureSpan">flow-bin.</span>64
1.  string <span class="apidocSignatureSpan">flow-bin.</span>65
1.  string <span class="apidocSignatureSpan">flow-bin.</span>66
1.  string <span class="apidocSignatureSpan">flow-bin.</span>67
1.  string <span class="apidocSignatureSpan">flow-bin.</span>68
1.  string <span class="apidocSignatureSpan">flow-bin.</span>69
1.  string <span class="apidocSignatureSpan">flow-bin.</span>7
1.  string <span class="apidocSignatureSpan">flow-bin.</span>70
1.  string <span class="apidocSignatureSpan">flow-bin.</span>71
1.  string <span class="apidocSignatureSpan">flow-bin.</span>72
1.  string <span class="apidocSignatureSpan">flow-bin.</span>73
1.  string <span class="apidocSignatureSpan">flow-bin.</span>74
1.  string <span class="apidocSignatureSpan">flow-bin.</span>75
1.  string <span class="apidocSignatureSpan">flow-bin.</span>76
1.  string <span class="apidocSignatureSpan">flow-bin.</span>77
1.  string <span class="apidocSignatureSpan">flow-bin.</span>78
1.  string <span class="apidocSignatureSpan">flow-bin.</span>79
1.  string <span class="apidocSignatureSpan">flow-bin.</span>8
1.  string <span class="apidocSignatureSpan">flow-bin.</span>80
1.  string <span class="apidocSignatureSpan">flow-bin.</span>81
1.  string <span class="apidocSignatureSpan">flow-bin.</span>82
1.  string <span class="apidocSignatureSpan">flow-bin.</span>83
1.  string <span class="apidocSignatureSpan">flow-bin.</span>84
1.  string <span class="apidocSignatureSpan">flow-bin.</span>85
1.  string <span class="apidocSignatureSpan">flow-bin.</span>86
1.  string <span class="apidocSignatureSpan">flow-bin.</span>87
1.  string <span class="apidocSignatureSpan">flow-bin.</span>88
1.  string <span class="apidocSignatureSpan">flow-bin.</span>89
1.  string <span class="apidocSignatureSpan">flow-bin.</span>9
1.  string <span class="apidocSignatureSpan">flow-bin.</span>90
1.  string <span class="apidocSignatureSpan">flow-bin.</span>91
1.  string <span class="apidocSignatureSpan">flow-bin.</span>92
1.  string <span class="apidocSignatureSpan">flow-bin.</span>93



# <a name="apidoc.module.flow-bin"></a>[module flow-bin](#apidoc.module.flow-bin)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
