# omultisafepay
3rd party Payment Provider Integration Solution for MultiSafePay&tm; as a separate and optional hot-deploy component.

##Development
Just put the following in the svn:externals properties of the hot-deploy folder of your OFBiz implementation for a checkout:

omultisafepay         https://github.com/ORRTIZ/omultisafepay/trunk

After having updated the hot-deploy folder (to execute the checkout from the repository), you'll need to build OFBiz again (./ant build) and load the seed, seed-initial and  - optionally- demo datasets.

