sa-node
=======

[![Build Status](https://travis-ci.org/softasap/sa-node.svg?branch=master)](https://travis-ci.org/softasap/sa-node)

Installs nodejs 0.10,0.12,4.X,5.X,6.X,7.X, as specified in nodejs_version version.

nodejs_version: "4.x" # 0.10 0.12 4.x 5.x 6.X 7.X


Usage example:

```YAML


     - {
         role: "sa-node",
         nodejs_version: "0.12",
         option_install_default_packages: True
       }


```


option_install_default_packages: 
```
      - gulp
      - bower
      - grunt  
      - grunt-cli
      - david
```


Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-node` role using the command


`
   ansible-galaxy install softasap.sa-node
`

the role will be available in the folder `library/softasap.sa-node`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-node"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

