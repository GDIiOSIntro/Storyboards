# Let's make an interface.

---

#Apple supports two ways of building user interfaces:

* Programmatic layout
* Interface Builder

---

## In Interface Builder you build interfaces with a tool called a Storyboard

---

#Why use a storyboard? 

---

# Form follows function
##Interface Builder lets you build visual things in a visual way.

---

##Why use a storyboard? 
###Objective-C and Swift are `compiled languages`.

---

##Why use a storyboard? 

###That means, if you want to change the size of a button by 1 point, you will need to re-build your entire app to see what that looks like. 

---

Making a button

```swift
let buttonFrame = CGRect(x: 0, y: 0, width: 50, height: 50)
let button = UIButton(frame: buttonFrame)
button.backgroundColor = UIColor.blackColor()
view.addSubview(button)
```

---

##This isn't true for front-end web development. 

---

# Let's build a small app interface.

---

#In this lesson, I'm going to cover:

* Interface Builder
* Storyboards
* Segues
* IBOutlets
* IBActions

---

#Let's look at Xcode.

---

#Key Takeaways: What is a Storyboard?
- Interface Builder is a tool in Xcode that lets you build screens in a visual way.
- Each sequence of screens is represented by a `Storyboard`

---

#Key Takeaways: Segues
- To move from one screen to another, use a `segue`.
  
- To make a segue, control-drag between a button and a new `View Controller`

---

#Key Takeaways: IBOutlets

- `IBOutlets` let you connect Storyboard views to files of code.
  
-To make an IBOutlet, control-drag from a view to a file.

---

#Key Takeaways: IBActions

- `IBActions` also let you connect Storyboard views to files of code.

- They let us program things to happen when the user interacts with a Storyboard view.

- To make an IBAction, control-drag from a view to a file.

---

#Important Troubleshooting Notes: 

For IBOutlets and IBActions to work, you need to set the IB `View Controller` to have the name of the file you are dragging the outlet or action to.

You can delete actions and outlets after you make them.

---

#Key Takeaways: XML
- Storyboards aren't not code -- they just let Apple write interface code for you.

- Apple writes storyboards in a language called `xml`.

- Keep this in mind but this will be more relevant to you later.

---

#Tips
- Don't rush - play around

- Use the menu on the upper right to show different parts of Xcode

- Google everything

---

#Let's do a lab:

#http://bit.ly/1LRwVfS














