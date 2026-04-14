<h2 class="c-project-heading--task">Align the columns</h2>

### Step 1

Make the columns `float` to the left or right.


### Step 2

Switch back to `style.css` and find the styles for `column1` and `column2`.



### Step 3

Add a `float` property to each column style so that one floats to the left and the other floats to the right.


<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 14
line_highlights: 16, 21
---
.column1 {
    width: 45%;
	float: left;
}

.column2 {
    width: 45%;
	float: right;
}

--- /code ---
</div>
### Step 4

Click **Run** and see your how your columns align.


<div class="c-project-output">

![ADD](images/step6.png)

</div>
