# vendor_miuicamera
Miui Camera for Mi note 3 Jason 

## Usage

```python
cd rom home directory

# cd rr
rr

# clone repo into vendor/miuicamera path
git clone https://github.com/enweazudaniel/vendor_miuicamera.git vendor/miuicamera

# Then include this path in device.mk if it doesn't exist 
$(call inherit-product-if-exists, vendor/miuicamera/common/common-vendor.mk)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
