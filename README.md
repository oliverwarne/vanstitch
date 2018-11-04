# van Stitch

van Stitch is a program that downloads the highest possible quality images from the [Van Gogh muesuem](https://www.vangoghmuseum.nl/en). The site *does* offer downloads of the images, but they are almost always low resolution. For example, [The Potato Eaters](https://www.vangoghmuseum.nl/en/collection/s0005V1962?v=1) will download as a 3840 x 2715 image from the site, but van Stitch will download the image at 7695 x 5441. 

## Installation
Clone the repo

```bash
git clone [thisrepo]
```

Use [pip](https://pip.pypa.io/en/stable/) to install the requirements.

```bash
pip install -r requirements.txt
```

## Usage

```python
./van_stitch --term "portrait as a painter"
### Download the classic "portrait as a painter"

./van_stitch --id s0146V1962
### Download van Gogh's Wheatfield

./van_stitch --term wheatfield --num 3 --artist "Vincent van Gogh"
### Download the first three paintings that wheatfield, by artist van Gogh
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
