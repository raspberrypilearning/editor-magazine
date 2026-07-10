## Align the columns

Make the columns `float` to the left or right.

## Step 1

Go back to `style.css` and find the styles for `column1` and `column2`.

## Step 2

Add a `float` property to each column style so that one floats to the left and the other floats to the right.


```css filename="style.css" line_numbers="true" line_number_start="14" line_highlights="16,21"
.column1 {
    width: 45%;
	float: left;
}

.column2 {
    width: 45%;
	float: right;
}

```

## Now run your code

See how your columns align.

![Visual preview showing the two floated columns side by side](images/step6.png)

