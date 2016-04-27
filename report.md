# Indiana Growth to Standard Model

The Indiana Growth to Standard Model is both a model for calculating/reporting individual student growth as well as a model
for summarizing individual student growth results for schools for the purpose of rating schools as part of the Indiana’s A-F grading
policy. Individual student learning (i.e., student growth) is a cornerstone of Indiana’s A to F accountability system for
schools. The incorporation of growth is done in accordance with the following values:

__Value 1:__ Schools should be held accountable for individual student learning (i.e., student growth).

__Value 2:__ Individual student growth is always considered relative to Indiana State standards: a student reaching or
maintaining proficiency. This is what is meant by growth to standard.

__Value 3:__ Growth should be a distinct metric, different from school performance status (percent proficient). The
metric should have a low correlation to performance.

Indiana has a long history of calculating and using student growth as part of the ISTEP+ assessment program. The development of the current Indiana Growth to Standard Model improved upon that work and involved overcoming several common misconceptions including:

* [Subtraction is not a growth model](https://view.literasee.io/Literasee/Indiana/report#subtraction-is-not-a-growth-model)


## A-F and Student Growth for Schools

Summarizing individual student growth at the school level in a manner consistent with the above mentioned values is performed
using a growth to proficiency table There a three pieces associated with the Indiana growth to proficiency table:

* The Prior Year Status of the student. That is, where the student performed the previous year.
* The individual student growth target ranges
* The points awarded for each student based upon the prior year status and where their observed growth falls within the
target range.

![alt text](https://raw.githubusercontent.com/Literasee/Indiana/master/Indiana_growth_table.png "Indiana Growth To Proficiency Value-Table")

The growth to proficiency table defines a set of prior year starting levels (Prior Year Status) and numeric growth ranges
(Target Ranges) that establish points to be awarded to schools based upon the goal of a student reaching/maintaining Pass status.
Because the ISTEP+ only reports 3 levels of performance (Did not pass, Pass, and Pass +) it was necessary to subdivide these
levels to detect student growth within the 3 larger categories. There are 8 total subdivided levels: Did not pass 1, 2, and 3
(DNP1, DNP2, DNP3), Pass 1, 2, and 3 (P1, P2, P3) and Pass + 1 and 2 (PP1, PP2). For students in DNP1, DNP2, or DNP3, the
expectation is for the student to move up levels each year to reach Pass status. For students in P1, P2, P3, PP1, or PP2, the
expectation is for the student to at least maintain their passing status and to, ideally, continue moving up, if possible.

The target ranges associated with each of the 8 subdivided levels indicate a range of student growth percentile associated with
low movement, standard movement, and high movement. Low movement is characteristic of a student dropping a level year over year, typical movement is characteristic of maintaining one's level year over year and high movement is characteristic of moving up a
level year over year. Based upon each students movement in a school, points indicated in the table are awarded. An average number
of growth points per student is calculated that is used as part of the A to F calculation.

### Example calculation

For simplicity sake, assume Brigg's Elementary School has 10 students with the following Prior Year Status and Observed Growth:

1. PP1 and 32
2. P1 and 67
3. P2 and 89
4. DNP1 and 72
5. P1 and 45
6. P2 and 34
7. DNP2 and 21
8. DNP3 and 40
9. PP2 and 89
10. P1 and 76

$$
\textrm{Growth Points} = \frac{50+150+150+175+100+50+0+100+150+150}{10}=107.5
$$  


---

## Subtraction is not a growth model

A common belief among users of ISTEP+ data is that one can simply subtract student scores from one grade to the next and use
those to evaluate student growth. Subtraction is what everyone learned to do in elementary schools when asked to find how
much a quantity had changed. As we’ll see, subtraction doesn’t address what we really want to look at. For the ISTEP+, there
are two problems with scale score subtraction.

1. The 2015-2016 scale is not comparable with the 2014-2015 scale. Subtracting scale scores is not possible.
2. Even when scale scores can be subtracted (as with ISTEP+ results from previous years.) One cannot evaluate growth
for students starting at different places because growth depends upon where a student starts.  

### A tale of two high jumpers

![alt text](https://raw.githubusercontent.com/Literasee/Indiana/master/high_jump_figure.png "Improvement for two high jumpers")

The reason for 2 is often not clear until one looks more closely at a simple example. Consider two high jumpers, Anna and
Judy. Anna is a novice higher jumper and Judy is a world class competitor. Anna’s best jump in 2013 was 3 feet 6 inches and
improved to 4 feet in 2014. Judy’s best jump in 2013 was 6 feet 7 inches and improved to 6 feet 9 inches in 2014.
Simple subtraction tells us how much each changed: 6 inches for Anna and 2 inches for Judy. However comparing Anna’s 6
inch improvement to Judy’s 2 inch improvement requires care.

Though it is certainly true that 6 inches is more than 2 inches, a 6 inch improvement for a novice is not more impressive than
a 2 inch improvement for an expert. Novices generally improve a lot when starting--often referred to as beginners gains.
Understanding Anna’s and Judy’s improvement requires one to compare them to their peer’s: those whose high jumping ability is
like theirs. A 2 inch increase for an elite high jumper is remarkable whereas 6 inches for a novice is typical.

The same holds with growth in ISTEP+ test scores. Like in the high jump example, changes for lower achieving students tend to
be much larger than those for high achieving students.
