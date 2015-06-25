# Tinkerbox Workflow
## Ted Johansson

### **Version Control**

#### **Commits should be...**

#### **Clean!**
* No comments
* No debug statements
* No TODO’s
* Passes style checks

_Pro tip: `git diff`_

#### **Atomic & islolated**
* One change, one commit

_Pro tip: If your commit message contains the word 'and', it's probably not isolated_

#### **Proper commit message**
* First line should be synopsis
* Include rationale for something complex, unconventional, controversial

_ie. Bad commit messages_
* Many fixes
* Fix navbar
* .

_ie. Good commit messages_
* Navbar now properly sticks to the top on mobile

#### **Things to think about**
* What is changed & why do we need this?
* Why did I pick this gem & why do we need this?
* Add environment variables, etc

### **Testing**

#### **TDD**

#### **gem `guard`**
* Automated testing ie. rubocop, rspec

### **Thinking**

#### **No code monkey workflow**

#### **Agile vs Waterfall**
* Tinkerbox promotes itself as an agile company
* Work should be split by feature not by functional decomposition/layer
* Although MVC is separation of concerns, we should not follow this style of working when it comes to developing a product
* Waterfall would also mean that you'll only be able to deliver at the end - client doesn't care if you show them a whole bunch of models that you've created, they want to see features

### **Caring**

Care about every part of the process!