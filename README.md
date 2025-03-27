# Zoocha Links Paragraph Installation Guide

To install the Zoocha Links Paragraph, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Add the below in the Drupal Root's composer.json installer-paths
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to execute the Zoocha Links Paragraph installation:

    ```sh
    ddev drush recipe recipes/custom/zr-para-links
    ```

This command will execute the Zoocha Links Paragraph installation.
