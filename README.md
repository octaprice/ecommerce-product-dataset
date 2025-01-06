# Octaprice Ecommerce Product Dataset Repository

![Octaprice Logo ](https://octaprice-assets.s3.us-east-1.amazonaws.com/LOGO_V2_PRETO_fundo+transparente.png)

## Introduction

Welcome to the [Octaprice](https://octaprice.com) Ecommerce Product Dataset Repository! This repository is created by [Octaprice](https://octaprice.com) and is dedicated to providing free datasets of publicly available product data from ecommerce websites. We release new datasets weekly, each containing around 1,000 products.

To get ongoing free access to additional datasets, you can use Octaprice's free [Dashboard](https://octaprice.com).

## Dataset Overview

- **Weekly Releases:** New dataset available every week..
- **Rich Metadata:** Includes product categories, images, prices, sellers and more.
- **Diverse Sources:** Products from a wide range of ecommerce websites.

## Dataset Description

Each dataset is provided in CSV format with accompanying metadata in JSON format. Here's what you can expect in each dataset:

### Product Information
- Product name and brand
- Description (both plain text and HTML format)
- MPN (Manufacturer Part Number)
- SKU
- ASIN (for Amazon products)
- Canonical URL
- Breadcrumb navigation path

### Pricing Data
- Current price
- Regular price
- Currency information
- Alternative seller prices
- Availability status

### Rich Media
- Main product image URL
- Additional product images
- Product variants (when available)

### Additional Metadata
- Product specifications
- Dimensions and weights
- Manufacturing details
- Country of origin
- Release/availability dates
- Category rankings
- Customer ratings and review counts
- Target audience
- Usage instructions
- Warranty information

### Sample Data Format
```json
{
    "brand": "Product Brand",
    "price": "00.00",
    "currency": "USD",
    "description": "Product description",
    "images": ["image_url_1", "image_url_2"],
    "additionalProperties": [
        {"name": "Property Name", "value": "Property Value"}
    ],
    "dateDownloaded": "YYYY-MM-DDThh:mm:ssZ",
    "reviewCount": 0000,
    "ratingValue": 0.0
}
```

## Usage

The datasets are free for academic, research, and journalistic purposes:

- **Market Research:** For price monitoring, competitive analysis, and market trends.
- **Product Analytics:** Suitable for product categorization and attribute extraction.
- **Business Intelligence:** Helps companies make data-driven pricing decisions.

## Accessing the Datasets

1. Navigate to the 'Datasets' folder in this repository
2. Select a dataset based on your requirements (each dataset contains ~1000 products)
3. Download both the dataset (.csv format) and its accompanying metadata file (.json)

## Support

For questions or support, raise an issue in the repository or contact us at [contact@octaprice.com](mailto:contact@octaprice.com).

## License/Terms of Use 

By using the Dataset Repository you agree to the following [TOU](https://github.com/octaprice/ecommerce-product-datasets/blob/master/tou.MD).

---
