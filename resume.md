[Home](README.md) | [About Me](aboutme.md) | [My Art and Comic](art.md) | [Contact Details](contact.md)

My resume which I desperately need to update!

Education - 
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
Bob Allee - Computer Aided Design Teacher - (573) xxx-xxxx  
Brittany Williamson - Art Teacher - (573) xxx-xxxx  

#### Here's some python code from previous assignments

##### Volume Calculator
``` open_file = input('Indicate the name of the file you would like to work with: ')

keys = ('name of file', 'count of numbers in file', 'sum of numbers', 'average of numbers', 'maximum value', 'minimum value', 'range of values')
values = 0
dictionary = dict.fromkeys(keys, values)
dictionary['name of file'] = open_file

with open(open_file) as get_data:
    contents = get_data.read().split()
# with block closes file after completion

for i in range(len(contents)):
    contents[i] = int(contents[i])

dictionary['count of numbers in file'] = len(contents)
dictionary['sum of numbers'] = sum(contents)
dictionary['average of numbers'] = sum(contents)/len(contents)
dictionary['maximum value'] = max(contents)
dictionary['minimum value'] = min(contents)
dictionary['range of values'] = dictionary['maximum value'] - dictionary['minimum value']

print('You can learn about the following file attributes: name, sum, count, average, max, min, range.')
def learning():
    learn_more = input('Please indicate what you would like to know more about: ')
    if learn_more == 'name':
        print(f"The name of the file is {dictionary['name of file']}.")
    elif learn_more == 'sum':
        print(f"The sum of numbers in the file is {dictionary['sum of numbers']}.")
    elif learn_more == 'count':
        print(f"The count of numbers in the file is {dictionary['count of numbers in file']}.")
    elif learn_more == 'average':
        print(f"The average number in the file is {dictionary['average of numbers']}.")
    elif learn_more == 'max':
        print(f"The maximum value of numbers in the file is {dictionary['maximum value']}.")
    elif learn_more == 'min':
        print(f"The maximum value of numbers in the file is {dictionary['minimum value']}.")
    elif learn_more == 'range':
        print(f"The range of numbers in the file is {dictionary['range of values']}.")
    else:
        print('Invalid input')

def run_again():
    yesno = input("Would you like to know more? y/n: ")
    if yesno == 'y':
        learning()
        run_again()
    else:
        exit()

learning()
run_again()
```

##### FizzBuzz Solution
``` function fizzbuzz() {  
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
}  
```

