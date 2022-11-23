# ECE444-F2022-Lab6
Peter Wang

# Deployed app
https://lab6-reactr.herokuapp.com/

# Test Cases
def test_post_and_get_recommendation():
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-7-waterfall/blob/main/Education_Pathways/tests/test_app.py#L47-L63

def test_validation_api():
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-7-waterfall/blob/main/Education_Pathways/tests/test_app.py#L67-L78

def test_related_courses():
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-7-waterfall/blob/main/Education_Pathways/tests/test_app.py#L94-L100

# Pros of TDD
TDD encourages modular design as you write tests at a unit level. This results in many benefits in the long term. For example, having more modular design makes it easier to maintain and refactor code as the modular nature of the code means that it is decoupled from other pieces of code. This means there are less dependencies in your code, thus making a single change won’t result in a cascade of other changes that need to be done. Additionally, having a test suite is a good to ensure that when changes occur, we have been guaranteed a minimum amount of coverage for any new bugs that may occur given that the test suite passes. This is crucial for long term projects where code is complex and any change may completely break the code, and allows less debugging.
# Cons of TDD
TDD takes a long time as you essentially must write a test for each piece of code you are writing. This can be very time consuming when the project is starting off. Similarly, if your quality requirements change throughout the project’s lifecycle, your code will have to reflect that and as a result tests need to be updated again. Furthermore, tests can find some bugs but not all bugs within your code. Certain bugs may slip through the tests you created, or the tests themselves have bugs in them that allow buggy code to pass. 
