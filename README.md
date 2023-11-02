# AutoBook
Automatic book writer system: generates entire "book" within 10-20 thousands word range. Includes 3 styles: learning, creative, technical/scientific.
Variables to set:
context_string is an example of the format of the output you require. (optional)
plot is an example of the format of the chapter outline you require. (optional)
task is main task for the book. Examples: task=f"""Create 10 chapter book that teaches all of the core concepts for accounting and finance, focused on teaching through examples and real-life cases.
                                    Provide examples, and applications. Include examples of mathematical solutions for examplar problems for specific applications.
                                    Clearity, efficency in word choice within it should be one main priorities. Information must be as specific as possible, also try to cite the sources when possible.
                                    """
chapter_total is total number of chapters in the book(set to chapter_total=15)
