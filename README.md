
# Linhnv_QuantityIncrement

## Description

The `Linhnv_QuantityIncrement` module for Magento 2 enhances the user experience on the category page by adding intuitive quantity increment and decrement buttons for each product. This feature allows customers to easily adjust the desired quantity of products directly from the category view, streamlining the shopping process and improving usability.

## Features

- **Increment/Decrement Buttons**: Adds '+' and '-' buttons next to the quantity input field for each product on the category page, allowing customers to increase or decrease the quantity with a single click.
- **Improved Usability**: Enhances the shopping experience by making it easier for customers to adjust quantities without navigating to the product detail page.
- **Responsive Design**: Ensures that the increment and decrement functionality works seamlessly across various devices and screen sizes.
- **Customizable**: Easily customizable to match the store's design and functionality requirements.
- **Admin Control**: Allows store administrators to enable or disable the feature as needed.

## Installation

### 1. Clone the repository

Navigate to the root directory of your Magento 2 installation and run the following command to clone the module:

\`\`\`bash
git clone <repository-url> app/code/Linhnv/QuantityIncrement
\`\`\`

Replace \`<repository-url>\` with the URL of your repository. For example:

\`\`\`bash
git clone https://github.com/yourusername/QuantityIncrement.git app/code/Linhnv/QuantityIncrement
\`\`\`

### 2. Enable the module

Run the following commands to enable and set up the module:

\`\`\`bash
php bin/magento module:enable Linhnv_QuantityIncrement
php bin/magento setup:upgrade
php bin/magento cache:clean
\`\`\`

## Usage

1. Navigate to the category page on your Magento 2 storefront.
2. For each product, you will see '+' and '-' buttons next to the quantity input field.
3. Click the '+' button to increment the quantity or the '-' button to decrement the quantity.
4. The input field will automatically update to reflect the selected quantity.

## Customization

- The appearance and position of the increment/decrement buttons can be customized by modifying the CSS and template files located in the \`view/frontend\` directory of the module.
- Additional functionality can be added by extending the JavaScript logic in \`quantity-increment.js\`.

## Technical Details

- **Module Namespace**: \`Linhnv\`
- **Module Name**: \`QuantityIncrement\`
- **Version**: 1.0.0
- **Dependencies**: Magento_Catalog

## Troubleshooting

### Common Issues

- **Module not showing up**:
  - Ensure the module is placed in the correct directory: \`app/code/Linhnv/QuantityIncrement\`.
  - Verify you have run all the necessary setup commands (\`setup:upgrade\`, \`cache:clean\`).

- **Errors during command execution**:
  - Make sure you are executing the commands from the root directory of your Magento 2 installation.
  - Check Magento error logs for more detailed information about the error.

## Contact

For customization requests or any further assistance, please contact us at:
- **Email**: linhdevelopment1902@gmail.com and linhnguyenvan1902@gmail.com
- **Phone**: +8435017700

## Conclusion

By following the instructions in this README, you can easily clone, install, and configure the `Linhnv_QuantityIncrement` module in your Magento 2 store. This module enhances the shopping experience on the category page by providing convenient quantity adjustment buttons, making it easier for customers to select the desired quantity of products quickly and intuitively.
