# HA-Mipow
Mipow LED Light support for Homeassistant

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

First clone this repository

```
git clone https://code.siemens.com/florian.frank/input-numeric.git
```

copy the .py in your /pathToHaConfig/custom_components/

### Usage
First get the mac adress of your mipow light. For example on linux:

```
sudo hcitool lescan
```

Add the following to your config.yaml

```
- platform: mipow
  devices:
    1:
      name: Light1
      mac: Mac-Adress-of-Light
    2:
      name: Light2
      mac: Mac-Adress-of-Light

```

## Authors

* **Florian Frank**

## License

See the [LICENSE.md](https://raw.githubusercontent.com/Der---Flo/HA-Mipow/master/LICENSE) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
