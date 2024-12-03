# True Insights  

**True Insights** is a streamlined web-based platform designed for creators to effortlessly collect anonymous Insights. The platform allows creators to sign up, generate unique Insights links, and receive Insights from users anonymously without requiring them to sign up.  

---

## Features  
- **Creator Account**: Creators can register, log in, and manage their Insights links.  
- **Anonymous Insights**: Users can submit Insights anonymously without creating an account.  
- **Unique Insights Links**: Creators can share custom-generated links for Insights collection.  
- **Responsive Design**: Optimized for seamless use across all devices.  
- **Secure and Reliable**: Ensures data privacy and anonymity for users and creators alike.  

---

## Tech Stack  

### Frontend  
- **React**  
- **Next.js**  
- **Tailwind CSS**  

### Backend  
- **Node.js**  
- **Express.js**  
- **MongoDB**  
- **Zod** for schema validation  

### Authentication  
- **Auth.js** for secure user authentication  

---

## Installation  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/Aksingh1205/True-Insights.git
   cd True-Insights
   ```

2. **Install dependencies**:  
   ```bash
   npm install
   ```

3. **Set up environment variables**:  
   Create a `.env` file in the root directory and configure the following variables:  
   ```env
   MONGODB_URI=your-mongodb-connection-string
   NEXTAUTH_URL=your-next-auth-url
   NEXTAUTH_SECRET=your-secret-key
   ```

4. **Run the development server**:  
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.  

---

## Usage  

1. **Creators**:  
   - Sign up for an account.  
   - Generate and share Insights links with your audience.  
   - View and manage Insights securely in your dashboard.  

2. **Users**:  
   - Click on the shared link to provide anonymous Insights.  
   - No login or signup required!  

---

## Future Enhancements  
- **Analytics Dashboard**: Insights for creators, including Insights trends and metrics.  
- **Customizable Insights Forms**: Allow creators to tailor the Insights form to their needs.  
- **Multi-language Support**: Enable the platform to cater to a global audience.  

---

## Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature-name
   ```  
3. Make your changes and commit them:  
   ```bash
   git commit -m "Add some feature"
   ```  
4. Push the changes:  
   ```bash
   git push origin feature-name
   ```  
5. Open a pull request.  

---

## License  

This project is licensed under the MIT License. See the `LICENSE` file for more details.  

---

## Acknowledgements  
- **React** for its robust UI framework.  
- **Next.js** for server-side rendering and routing.  
- **Auth.js** for secure authentication.  
- **MongoDB** for efficient data storage.  

Feel free to reach out for any questions or support. Happy coding! 🚀
