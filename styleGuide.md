*Click 'Raw' on the [SRS Style Guide](https://github.com/voyager1winterberry/cse372-01srs/blob/main/styleGuide.md) to see markdown syntax in use.*

*[Markdown Tutorial](https://www.markdownguide.org/basic-syntax/)*

## Main Header
Anything with one decimal or less will be a main header.

### Sub Header
Sub header level should match the number of decimal places + 1 on the subcategory. For example, 1.3.1 would be a third level subheader in markdown preceded by ###. 1.3.1.2 would be preeceded by ####.

- Bullet/List Items
* Also a bulleted list
1. Number lists

**Bold Stuff**
Used to distinguish words that have definition in glossary.

*Italic Text*

To create paragraphs, use a blank line to separate one or more lines of text.

[Internal Document Linking](#main-header)
* Each subsection should be added to the table of contents.
* Used to quickly jump to sub headers within document.
* Syntax: [Description of link] + (#section-name)

### Writing Style Requirements:
Use the word 'shall' when appropriate. For example, "The application shall only accept input within appropriate parameters."

## Section 1.4: Definitions
- The definitions shall be placed within one table.
- New definitions that are added to the definition table shall (excluding the one exception of referencing another definition as the definition) be formatted as follows: | Word or phrase being defined | Definition of said word or phrase. |
- There shall be periods at the end of each definition, except in the case of a definition that references another definition.
- Word or phrases which contain a definition that is a reference to another definition shall be formatted as such: | Trainer | see *Personal Trainer* |
- There shall be no use of colons in the section of the table containing the word or phrase being defined.

## Section 3
Section 3 shall be ordered based on feature (myTrainer, myGymMap, myVideos, myWorkouts, Home Page, Login Page). Attributes for the feature shall then be listed in the following order: 
1. External Interface 
2. Functions
3. Usability Requirements
4. Performance Requirements
5. Logical Database Requirements
6. Design Constraints 
7. Software System Attributes

Section 3, in its entirety, shall have the following order for each feature:
- 3.1 myTrainer
- 3.1.1 External Interfaces
- Content about external interfaces
- 3.1.2 Functions
- Content about functions
- 3.1.3 Usability Requirements
- Content about usability requirements
- 3.1.4 Performance Requirements
- Content about performance requirements
- 3.1.5 Logical Database Requirements
- Content about logical database requirements
- 3.1.6 Design Constraints
- Content about design constraints
- 3.1.7 Software System Attributes
- Content about software system attributes