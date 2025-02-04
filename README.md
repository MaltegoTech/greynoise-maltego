[![main](https://github.com/GreyNoise-Intelligence/greynoise-maltego/workflows/python_linters/badge.svg)](https://github.com/GreyNoise-Intelligence/greynoise-maltego/actions?query=workflow%3Apython_linters)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# GreyNoise Maltego Transform for Community API

This repo includes a transform for Maltego to query the GreyNoise Community API.

More details about Maltego here: [https://www.maltego.com/](https://www.maltego.com/)

## Usage

### Initial Configuration
In order to use the GreyNoise transform, install the Integration from the Transform Hub.  Then,
configure the transform using a GreyNoise API key.

If you don't have a GreyNoise API key, you can sign up for a free trial at
[https://viz.greynoise.io/signup](https://viz.greynoise.io/signup)


# Instructions for running locally in Maltego

1. Clone this repo to /repos/ (you may use an alternate directory, but will need to update the
   transforms after import)
2. Create a local virtual environment named repos/venv
3. Import ``greynoise.mtz`` into Maltego
4. Go to `Transforms` -> `Transform Manager`
5. Find the ``GreyNoiseCommunityIPLookup`` transforms, and update the
   ``commandline`` and ``working directory`` settings to match that of your local setup
6. Update the ``api_key`` in the ``transforms/GreyNoiseCommunityIPLookup.py`` file

# Values for creating a Manual Transform Seed

`ID`: `GreyNoise Community`
`Name`: `GreyNoise Community`
`Seed URL`: `https://cetas.paterva.com/runner/showseed/greynoisecommunity`
`Icon URL`: `https://viz.greynoise.io/favicon.ico`

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull
requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see
the [tags on this repository](https://github.com/GreyNoise-Intelligence/greynoise-maltego/tags).

## Authors

* **Brad Chiappetta** - *Initial work* - [bradchiappetta](https://github.com/bradchiappetta)

See also the list of [contributors](https://github.com/GreyNoise-Intelligence/greynoise-maltego/contributors) who participated
in this project.

## Acknowledgments

* Siemplify Community and Support members for help with the initial development.

## Links

* [GreyNoise.io](https://greynoise.io)
* [GreyNoise Terms](https://greynoise.io/terms)
* [GreyNoise Developer Portal](https://developer.greynoise.io)
* [GreyNoise Community API Reference](https://developer.greynoise.io/reference/community-api#get_v3-community-ip)

## Contact Us

Have any questions or comments about GreyNoise? Contact us at [hello@greynoise.io](mailto:hello@greynoise.io)

## Copyright and License

Code released under [MIT License](LICENSE).

