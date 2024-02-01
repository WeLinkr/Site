# WeLinkr
Connect, share, and discover. Join a vibrant community where connections spark creativity and conversations thrive.

## Running the Application

To run the WeLinkr site locally on your machine, follow these steps:

1. **Clone the Repository**: 
   ```
   git clone https://github.com/welinkr/site.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd site
   ```

3. **Install Dependencies**:
   ```
   npm install
   ```

4. **Run the Development Server**:
   ```
   npm run dev
   ```

5. **Access the Website**:
   Once the server is running, you can access the website by navigating to `http://localhost:3000` in your web browser.

## localhost:PORT Configuration

By default, the WeLinkr site is assigned to `localhost:3000` when running in development mode (`npm run dev`). However, if you need to configure a different port, you can do so by modifying the `package.json` file and changing `next dev -p PORT` or by passing an environment variables to the `npm run dev -p PORT` command.
