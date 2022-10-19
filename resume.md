[Home](README.md) | [About Me](aboutme.md) | [My Art and Comic](art.md) | [Contact Details](contact.md)
My resume which I desperately need to update!

Education
2015 graduate of Hallsville High School, Hallsville, Missouri 
Associate of Arts degree awarded by Moberaly Area Community College
4.0 GPA with MACC
Student at University of Missouri majoring in Information Technology

2013 - 2015: Columbia Area Career Center, Columbia, Missouri
Digital Media
Computer Aided Design
Graphic Design
3D Animation and Modeling

Employment History
Gerbes - July 15th, 2015 - April 20th, 2016
Employed as a Courtesy Clerk and worked part time as head of Scanning department.
University of Missouri Hospital - October 5th, 2015 - Present
Employed as a Nutrition Associate. Kitchen duties and patient-facing services.

Skills and Abilities
Experience with: Adobe Photoshop, Illustrator, InDesign, Premiere; Microsoft Word, PowerPoint, Excel;
Coding experience including HTML, CSS, Javascript, and Python
Knowledge in the use of Adobe programs such as Photoshop, Illustrator, InDesign, and Premiere
Experience with Autodesk programs and knowledge in primary architecture, civil engineering drawing, and moderate knowledge in 3D animation and modeling

References

Bob Allee
Computer Aided Design Teacher
(573) 673-9309

Brittany Williamson
Art Teacher
(573) 999-5037

Melissa Finaly
Guidance Counselor
mfinlay@hallsville.org 

#### Here's some python code from previous assignments
##### Volume Calculator
fkdsfkd
` print("Let\'s find the volume of a cylinder.")

run_program = True
while (run_program):
    while (True):
        try:
            r = float(input("Enter the radius of the cylinder: "))
            if (r < 0):
                print("Please enter a non negative value.")
                continue
        except ValueError:
            print("Input invalid. Please enter a numerical value.")
        else:
            break

    while (True):
        try:
            h = float(input("Enter the height of the cylinder: "))
            if (h < 0):
                print("Please enter a non negative value.")
                continue
        except ValueError:
            print("Input invalid. Please enter a numerical value.")
        else:
            break
    import math
    volume = math.pi * r**2 * h
    print("The volume of your cylinder is", volume)

    go_again = (input("Would you like to perform another calculation? y/n: "))
    if go_again != "y":
        run_program = False `

##### FizzBuzz solution
` function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i <= 100; i++) {
		if (i % 3 === 0 && i % 5 === 0) {
			displayHTML += "<p>" + 'FizzBuzz' + "</p>";
		} else if (i % 3 === 0) {
			displayHTML += "<p>" + 'Fizz' + "</p>";
		} else if (i % 5 === 0) {
			displayHTML += "<p>" + 'Buzz' + "</p>";
		} else
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML
} `
