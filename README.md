# Image Roaster

**Tired of not having friends to roast you? No worries! Just upload your photo to Image Roaster, and voilà—you'll get a roasting buddy! 🤣**

## Live Demo

Check out our [Live Demo](https://image-roaster.hafizhibnusyam.xyz/)!

![Image Thumbnail](https://github.com/hafizhlf/image-roaster/blob/remove-social-links/ss/Roasting-Foto.png)

## Requirements

To run this application, you will need the following:

1. Node.js (version ≥ 20 or LTS)
2. An API key from any LLM provider (Gemini is the example used here)

## Installation & Usage

Follow these simple steps to get started:

1. Clone this repository:
   ```
   git clone https://github.com/hafizhlf/image-roaster/tree/remove-social-links
   ```
2. Navigate to the project directory:
   ```
   cd image-roaster
   ```
3. Install the required packages and dependencies:
   ```
   npm install
   ```
4. Configure your environment variables:
   ```
   cd .env.copy .env
   ```
5. Start the server:
   ```
   npm start
   ```
6. Open your web browser and visit http://localhost:3000 to see the app in action!

## Prompt Configuration

Currently, prompts are statically defined to maintain simplicity in the application design. If you're interested in implementing a dynamic prompt feature, we encourage you to create a pull request. Here's a basic overview of how you might approach this:

1. **Identify the Static Prompts**: Locate the section in the code where prompts are defined, and consider how these could be made configurable. 

2. **Implement Dynamic Prompts**: Create a system that allows users to input or modify prompts via the user interface or an external configuration file.

3. **Testing**: Thoroughly test the new functionality to ensure that dynamic prompts work as intended and do not introduce any bugs.

4. **Documentation Updates**: Update this README and any other relevant documentation to reflect changes made to the prompt configuration process.

## Troubleshooting

If you encounter any issues while running the application, here are some common troubleshooting tips:

- **Dependency Errors**: Ensure that Node.js and npm are properly installed. Use `node -v` and `npm -v` to check your versions.

- **Failed to Start Server**: Verify that your `.env` file is correctly configured with your API key. Double-check the structure of your secrets.

- **CORS Issues**: If you run into cross-origin request issues, check your browser's console for detailed error messages.

## FAQ

**Q: Can I use my own images for roasting?**  
A: Yes! Our application allows you to upload your own photos for roasting.

**Q: Is there a limit on the image size?**  
A: Yes, the maximum image size limit is **10MB**. To ensure optimal performance, we recommend keeping your images under this limit.

**Q: Can I modify the code for my own purposes?**  
A: Absolutely! This project is open-source, and you can modify it as per your needs. Just remember to follow the licensing guidelines.

## License

You are free to use, modify, and even redistribute this project. If you choose to use it in a business context, we kindly ask that you provide proper attribution.

**Happy Roasting!** 🎉
