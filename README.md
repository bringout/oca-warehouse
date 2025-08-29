# OCA Warehouse

This repository contains **12** OCA packages for warehouse.

## Packages Included (12 packages)

- **odoo-bringout-oca-stock-logistics-barcode-barcodes_generator_abstract** - From stock: logistics_barcode_barcodes_generator_abstract
- **odoo-bringout-oca-stock-logistics-barcode-barcodes_generator_location** - From stock: logistics_barcode_barcodes_generator_location
- **odoo-bringout-oca-stock-logistics-barcode-barcodes_generator_package** - From stock: logistics_barcode_barcodes_generator_package
- **odoo-bringout-oca-stock-logistics-barcode-barcodes_generator_product** - From stock: logistics_barcode_barcodes_generator_product
- **odoo-bringout-oca-stock-logistics-barcode-product_barcode_constraint_per_company** - From stock: logistics_barcode_product_barcode_constraint_per_company
- **odoo-bringout-oca-stock-logistics-barcode-product_multi_barcode** - From stock: logistics_barcode_product_multi_barcode
- **odoo-bringout-oca-stock-logistics-barcode-product_multi_barcode_constraint_per_company** - From stock: logistics_barcode_product_multi_barcode_constraint_per_company
- **odoo-bringout-oca-stock-logistics-barcode-product_multi_barcode_stock_menu** - From stock: logistics_barcode_product_multi_barcode_stock_menu
- **odoo-bringout-oca-stock-logistics-barcode-product_packaging_multi_barcode** - From stock: logistics_barcode_product_packaging_multi_barcode
- **odoo-bringout-oca-stock-logistics-barcode-stock_barcodes** - From stock: logistics_barcode_stock_barcodes
- **odoo-bringout-oca-stock-logistics-barcode-stock_barcodes_picking_batch** - From stock: logistics_barcode_stock_barcodes_picking_batch
- **odoo-bringout-oca-stock-logistics-barcode-stock_picking_product_barcode_report** - From stock: logistics_barcode_stock_picking_product_barcode_report


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-warehouse/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-warehouse/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-warehouse/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-warehouse/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.
