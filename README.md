# Interactive Resume Builder

An all-in-one interactive resume/CV builder built with HTML, CSS, and JavaScript. This application allows users to create and manage their resume directly in the browser. All data is stored locally using `localStorage`, ensuring privacy and persistence between sessions.

## Features

- **Interactive Editing**: Add, edit, or remove personal information, profile picture, skills, experience, education, and certificates.
- **Profile Picture Upload**: Upload and display your profile picture.
- **Dynamic Rendering**: Resume updates in real-time upon saving changes.
- **Local Data Storage**: Data is saved in the browser's `localStorage`.
- **Single File Application**: Entire application contained within one HTML file.
- **User-Friendly Interface**: Simple and intuitive design for ease of use.

## How to Use

1. **Download the Project**
   - Clone the repository or download the `interactive_resume.html` file.

2. **Open the Application**
   - Open the `interactive_resume.html` file in a modern web browser (Chrome, Firefox, etc.).

3. **Edit Your Resume**
   - Click the **"Edit Profile"** button to open the edit form.
   - Fill in your personal information, upload a profile picture, and add sections as needed.
   - Click **"Save Changes"** to update your resume.

4. **Data Persistence**
   - Your data is stored locally; you can close and reopen the browser without losing your resume.

## Requirements

- A modern web browser with JavaScript enabled.

## Customization

- **Styling**
  - Modify the CSS within the `<style>` tags to change fonts, colors, and layout.

- **Additional Fields**
  - Extend the data object and forms to include more information like languages, hobbies, etc.
  - Update the `saveData()`, `populateForm()`, and `renderResume()` functions accordingly.

## Limitations

- **Browser Compatibility**
  - Use a modern browser that supports `localStorage` and the `FileReader` API.

- **Data Portability**
  - Data is stored locally and does not sync across devices or browsers.

## License

This project is open-source and available under the [MIT License](LICENSE).

