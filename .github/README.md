<p align="center">
    <img src="https://s19.postimg.org/jblfytw9f/laradock-logo.jpg" alt="Laradock Logo"/>
</p>

## How to setup ssl with laradock?

To setup ssl certificate with nginx in laradock, follow these steps:

1. Generate certificates manually using certbot: sudo certbot certonly --manual
2. Verify by trasnfering the files to the server and running nginx on http
3. Once the domain is verified, transfer the certificate files in the laradock/nginx folder
4. Build the nginx image again
5. Modify conf file to accept requests on 443

## Contributors

#### Core contributors:
- [Mahmoud Zalt](https://github.com/Mahmoudz) @mahmoudz | [Twitter](https://twitter.com/Mahmoud_Zalt) | [Site](http://zalt.me)
- [Bo-Yi Wu](https://github.com/appleboy) @appleboy | [Twitter](https://twitter.com/appleboy)
- [Philippe Trépanier](https://github.com/philtrep) @philtrep
- [Mike Erickson](https://github.com/mikeerickson) @mikeerickson
- [Dwi Fahni Denni](https://github.com/zeroc0d3) @zeroc0d3
- [Thor Erik](https://github.com/thorerik) @thorerik
- [Winfried van Loon](https://github.com/winfried-van-loon) @winfried-van-loon
- [TJ Miller](https://github.com/sixlive) @sixlive
- [Yu-Lung Shao (Allen)](https://github.com/bestlong) @bestlong
- [Milan Urukalo](https://github.com/urukalo) @urukalo
- [Vince Chu](https://github.com/vwchu) @vwchu
- [Huadong Zuo](https://github.com/zuohuadong) @zuohuadong
- Join us, by submitting 20 useful PR's.

#### Awesome contributors:

<a href="https://github.com/laradock/laradock/graphs/contributors"><img src="https://opencollective.com/laradock/contributors.svg?width=890" /></a>


## Donations

> Help keeping the project development going, by [contributing](http://laradock.io/contributing) or donating a little. 
> Thanks in advance.

Donate directly via [Paypal](https://www.paypal.me/mzalt)

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/mzalt) 

or become a backer on [Open Collective](https://opencollective.com/laradock#backer)

<a href="https://opencollective.com/laradock#backers" target="_blank"><img src="https://opencollective.com/laradock/backers.svg?width=890"></a>

or show your support via [Beerpay](https://beerpay.io/laradock/laradock) 

[![Beerpay](https://beerpay.io/laradock/laradock/badge.svg?style=flat)](https://beerpay.io/laradock/laradock)


## License

[MIT License](https://github.com/laradock/laradock/blob/master/LICENSE)
