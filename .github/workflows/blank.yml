{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![rmotr](https://user-images.githubusercontent.com/7065401/52071918-bda15380-2562-11e9-828c-7f95297e4a82.png)\n",
    "<hr style=\"margin-bottom: 40px;\">\n",
    "\n",
    "<img src=\"https://user-images.githubusercontent.com/7065401/58563302-42466a80-8201-11e9-9948-b3e9f88a5662.jpg\"\n",
    "    style=\"width:400px; float: right; margin: 0 40px 40px 40px;\"></img>\n",
    "\n",
    "# Exercises\n",
    "## Bike store sales"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![purple-divider](https://user-images.githubusercontent.com/7065401/52071927-c1cd7100-2562-11e9-908a-dde91ba14e59.png)\n",
    "\n",
    "## Hands on! "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np\n",
    "import pandas as pd\n",
    "import matplotlib.pyplot as plt\n",
    "\n",
    "%matplotlib inline"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "sales = pd.read_csv(\n",
    "    'data/sales_data.csv',\n",
    "    parse_dates=['Date'])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "sales.head()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### What's the mean of `Customers_Age`?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {
    "cell_type": "hint"
   },
   "source": [
    "Why don't you try with `.mean()`"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Customer_Age'].mean()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>density (KDE)</b> and a <b>box plot</b> with the `Customer_Age` data:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Customer_Age'].plot(kind='kde', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Customer_Age'].plot(kind='box', vert=False, figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### What's the mean of `Order_Quantity`?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Order_Quantity'].mean()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>histogram</b> and a <b>box plot</b> with the `Order_Quantity` data:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Order_Quantity'].plot(kind='hist', bins=30, figsize=(14,6))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Order_Quantity'].plot(kind='box', vert=False, figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many sales per year do we have?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Year'].value_counts()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>pie plot</b> with the previous data:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Year'].value_counts().plot(kind='pie', figsize=(6,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many sales per month do we have?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Month'].value_counts()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>bar plot</b> with the previous data:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Month'].value_counts().plot(kind='bar', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Which country has the most sales `quantity of sales`?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Country'].value_counts().head(1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Country'].value_counts()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>bar plot</b> of the sales per country:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Country'].value_counts().plot(kind='bar', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Create a list of every product sold"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "#sales.loc[:, 'Product'].unique()\n",
    "\n",
    "sales['Product'].unique()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Create a **bar plot** showing the 10 most sold products (best sellers):"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Product'].value_counts().head(10).plot(kind='bar', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Can you see any relationship between `Unit_Cost` and `Unit_Price`?\n",
    "\n",
    "Show a <b>scatter plot</b> between both columns."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales.plot(kind='scatter', x='Unit_Cost', y='Unit_Price', figsize=(6,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Can you see any relationship between `Order_Quantity` and `Profit`?\n",
    "\n",
    "Show a <b>scatter plot</b> between both columns."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales.plot(kind='scatter', x='Order_Quantity', y='Profit', figsize=(6,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Can you see any relationship between `Profit` per `Country`?\n",
    "\n",
    "Show a grouped <b>box plot</b> per country with the profit values."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales[['Profit', 'Country']].boxplot(by='Country', figsize=(10,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Can you see any relationship between the `Customer_Age` per `Country`?\n",
    "\n",
    "Show a grouped <b>box plot</b> per country with the customer age values."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales[['Customer_Age', 'Country']].boxplot(by='Country', figsize=(10,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Add and calculate a new `Calculated_Date` column\n",
    "\n",
    "Use `Day`, `Month`, `Year` to create a `Date` column (`YYYY-MM-DD`)."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Calculated_Date'] = sales[['Year', 'Month', 'Day']].apply(lambda x: '{}-{}-{}'.format(x[0], x[1], x[2]), axis=1)\n",
    "\n",
    "sales['Calculated_Date'].head()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Parse your `Calculated_Date` column into a datetime object"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Calculated_Date'] = pd.to_datetime(sales['Calculated_Date'])\n",
    "\n",
    "sales['Calculated_Date'].head()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How did sales evolve through the years?\n",
    "\n",
    "Show a <b>line plot</b> using `Calculated_Date` column as the x-axis and the count of sales as the y-axis."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Calculated_Date'].value_counts().plot(kind='line', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Increase 50 U$S revenue to every sale"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "#sales['Revenue'] = sales['Revenue'] + 50\n",
    "\n",
    "sales['Revenue'] += 50"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many orders were made in `Canada` or `France`?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales.loc[(sales['Country'] == 'Canada') | (sales['Country'] == 'France')].shape[0]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many `Bike Racks` orders were made from Canada?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales.loc[(sales['Country'] == 'Canada') & (sales['Sub_Category'] == 'Bike Racks')].shape[0]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many orders were made in each region (state) of France?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "france_states = sales.loc[sales['Country'] == 'France', 'State'].value_counts()\n",
    "\n",
    "france_states"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>bar plot</b> with the results:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "france_states.plot(kind='bar', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many sales were made per category?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Product_Category'].value_counts()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>pie plot</b> with the results:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Product_Category'].value_counts().plot(kind='pie', figsize=(6,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many orders were made per accessory sub-categories?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "accessories = sales.loc[sales['Product_Category'] == 'Accessories', 'Sub_Category'].value_counts()\n",
    "\n",
    "accessories"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>bar plot</b> with the results:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "accessories.plot(kind='bar', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many orders were made per bike sub-categories?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "bikes = sales.loc[sales['Product_Category'] == 'Bikes', 'Sub_Category'].value_counts()\n",
    "\n",
    "bikes"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Go ahead and show a <b>pie plot</b> with the results:"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "bikes.plot(kind='pie', figsize=(6,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Which gender has the most amount of sales?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Customer_Gender'].value_counts()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales['Customer_Gender'].value_counts().plot(kind='bar')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many sales with more than 500 in `Revenue` were made by men?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales.loc[(sales['Customer_Gender'] == 'M') & (sales['Revenue'] == 500)].shape[0]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Get the top-5 sales with the highest revenue"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "sales.sort_values(['Revenue'], ascending=False).head(5)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Get the sale with the highest revenue"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "#sales.sort_values(['Revenue'], ascending=False).head(1)\n",
    "\n",
    "cond = sales['Revenue'] == sales['Revenue'].max()\n",
    "\n",
    "sales.loc[cond]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### What is the mean `Order_Quantity` of orders with more than 10K in revenue?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "cond = sales['Revenue'] > 10_000\n",
    "\n",
    "sales.loc[cond, 'Order_Quantity'].mean()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### What is the mean `Order_Quantity` of orders with less than 10K in revenue?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "cond = sales['Revenue'] < 10_000\n",
    "\n",
    "sales.loc[cond, 'Order_Quantity'].mean()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many orders were made in May of 2016?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "cond = (sales['Year'] == 2016) & (sales['Month'] == 'May')\n",
    "\n",
    "sales.loc[cond].shape[0]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### How many orders were made between May and July of 2016?"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "cond = (sales['Year'] == 2016) & (sales['Month'].isin(['May', 'June', 'July']))\n",
    "\n",
    "sales.loc[cond].shape[0]"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Show a grouped <b>box plot</b> per month with the profit values."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "profit_2016 = sales.loc[sales['Year'] == 2016, ['Profit', 'Month']]\n",
    "\n",
    "profit_2016.boxplot(by='Month', figsize=(14,6))"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)\n",
    "\n",
    "### Add 7.2% TAX on every sale `Unit_Price` within United States"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# your code goes here\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "cell_type": "solution"
   },
   "outputs": [],
   "source": [
    "#sales.loc[sales['Country'] == 'United States', 'Unit_Price'] = sales.loc[sales['Country'] == 'United States', 'Unit_Price'] * 1.072\n",
    "\n",
    "sales.loc[sales['Country'] == 'United States', 'Unit_Price'] *= 1.072"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![purple-divider](https://user-images.githubusercontent.com/7065401/52071927-c1cd7100-2562-11e9-908a-dde91ba14e59.png)"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.1"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
