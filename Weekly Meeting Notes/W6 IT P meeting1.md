### Progress Check

1. **Docker Compose Diagram**
   - A visual representation of how Docker services are orchestrated.
2. **Database Design Diagram**
   - A visual representation outlining the structure of the database, including tables, fields, and how they are interconnected.
3. **Reuse Plan**
   - A strategic plan indicating how existing assets, code, or functionalities can be reused to save time and resources.
4. **Layered Architecture Diagram**
   - A visual representation of the software architecture, depicting different layers of abstraction and how they interact.

### Website Design Features

#### Client Requirements:

- The client requires a toolbar and a navbar allowing the admin to switch between different pages at any time.
- Next to the toolbar should be the entire webpage, and the client desires intuitive interaction, allowing sections or content of the webpage to be modified upon clicking.
- The contents such as events, courses, etc., are to be stored in the database.

#### Toolbar:

##### Add Element:

- **Text Editing:**
  - The client should be able to edit text, including text color, size, and font. The default font and the currently used font should be available.
- **Image Editing:**
  - Clients should be able to upload images as per their requirements. However, a specific format will be defined, and images exceeding the format size will need to be cropped.

##### Change of Subsection:

- Clients should be able to move different sections within the same page.

#### Navbar:

- For page navigation.
- The toolbar remains constant.

### Conceptual Design:

#### Toolbar:

- Text Editor:
  - Allows for modifications in text color, size, and font. Provides options for the default font and the current font in use.
- Image Editor:
  - Enables clients to upload images as needed, with a specific format defined. Images exceeding the format size must be cropped to fit.

#### Subsection Modification:

- Empowers clients to rearrange different sections within the same page, providing flexibility in displaying content as per preference.

#### Navbar:

- Facilitates seamless navigation between pages, with the toolbar remaining constant, ensuring uniformity and ease of access across different sections of the website.