## Tables
   1. Difference between \begin{table} and \begin{tabular}
        a. Tabular is just to create simple tables
        b. Table has additional functionality like caption, spaces etc

   2. Create spaces between cells with \def\arraystretch{1.5}
   3. Create caption with \caption{}
   4. If you need a paragraph in a cell while defining tabular \tabular{|l | p{2cm} |} where 2cm is the width of the paragraph
   5. \usepackage{float} to make the table appear where you are typing it and not at the bottom


## Arrays
  1. Not exactly arrays but to write numbered equations
  2. \begin{align} or \begin{align*}. Without the * numbers the equations. Else it doesn't
  3. If you want the '=' to be aligned for every equation, write &= in each equation
