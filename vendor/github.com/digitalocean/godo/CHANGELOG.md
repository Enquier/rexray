# Change Log

## [v1.2.0] - 2018-05-08

- #166 Remove support for Go 1.6 - @iheanyi
- #165 Add support for Let's Encrypt Certificates - @viola

## [v1.1.3] - 2018-03-07

- #156 Handle non-json errors from the API - @aknuds1
- #158 Update droplet example to use latest instance type - @dan-v

## [v1.1.2] - 2018-03-06

- #157 storage: list volumes should handle only name or only region params - @andrewsykim
- #154 docs: replace first example with fully-runnable example - @xmudrii
- #152 Handle flags & tag properties of domain record - @jaymecd

## [v1.1.1] - 2017-09-29

- #151 Following user agent field recommendations - @joonas
- #148 AsRequest method to create load balancers requests - @lukegb

## [v1.1.0] - 2017-06-06

### Added
- #145 Add FirewallsService for managing Firewalls with the DigitalOcean API. - @viola
- #139 Add TTL field to the Domains. - @xmudrii

### Fixed
- #143 Fix oauth2.NoContext depreciation. - @jbowens
- #141 Fix DropletActions on tagged resources. - @xmudrii

## [v1.0.0] - 2017-03-10

### Added
- #130 Add Convert to ImageActionsService. - @xmudrii
- #126 Add CertificatesService for managing certificates with the DigitalOcean API. - @viola
- #125 Add LoadBalancersService for managing load balancers with the DigitalOcean API. - @viola
- #122 Add GetVolumeByName to StorageService. - @protochron
- #113 Add context.Context to all calls. - @aybabtme
