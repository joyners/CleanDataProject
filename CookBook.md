Source of this data is from the class project assignment for Getting Clean Data

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The end result of this project is a tidy data set with with the average of each variable for each activity and each subject.


These are the goals outlined from the class:
	1.	Merges the training and the test sets to create one data set.
	2.	Extracts only the measurements on the mean and standard deviation for each measurement. 
	3.	Uses descriptive activity names to name the activities in the data set
	4.	Appropriately labels the data set with descriptive variable names. 
	5.	Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 


Column headers:

<TABLE FRAME=VOID CELLSPACING=0 COLS=1 RULES=NONE BORDER=0>
	<COLGROUP><COL WIDTH=213></COLGROUP>
	<TBODY>
		<TR>
			<TD WIDTH=213 HEIGHT=18 ALIGN=LEFT>subject</TD>
		</TR>
		<TR>
			<TD HEIGHT=18 ALIGN=LEFT>activity</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyacc-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyacc-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyacc-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyacc-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyacc-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyacc-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityacc-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityacc-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityacc-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityacc-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityacc-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityacc-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerk-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerk-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerk-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerk-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerk-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerk-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyro-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyro-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyro-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyro-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyro-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyro-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerk-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerk-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerk-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerk-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerk-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerk-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccmag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityaccmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tgravityaccmag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerkmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodyaccjerkmag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyromag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyromag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerkmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>tbodygyrojerkmag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyacc-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyacc-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyacc-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyacc-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyacc-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyacc-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccjerk-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccjerk-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccjerk-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccjerk-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccjerk-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccjerk-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodygyro-mean-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodygyro-mean-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodygyro-mean-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodygyro-std-x</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodygyro-std-y</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodygyro-std-z</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodyaccmag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodybodyaccjerkmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodybodyaccjerkmag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodybodygyromag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodybodygyromag-std</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodybodygyrojerkmag-mean</TD>
		</TR>
		<TR>
			<TD HEIGHT=19 ALIGN=LEFT>fbodybodygyrojerkmag-std</TD>
		</TR>
	</TBODY>
</TABLE>
