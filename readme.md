# Spider Community Blacklist

Welcome to the Spider Community Blacklist repository! This repository allows the Spider community to contribute to a curated list of domains that should be excluded from data collection by the Spider extension. Our aim is to ensure privacy and respect user preferences by allowing you to help define which sites should not be harvested for data.

## How It Works

The domains listed in this repository are automatically excluded from data collection by the Spider extension. This means that any activity on these sites will not be tracked, ensuring that sensitive information remains private and secure.

## Contributing

We welcome contributions from the community to help keep our blacklist comprehensive and up-to-date. Here's how you can contribute:

### Adding a New Domain

1. **Fork the Repository**  
   Start by forking this repository to your GitHub account.

2. **Clone the Repository**  
   Clone your forked repository to your local machine:

   ```
   git clone https://github.com/your-username/spider-blacklist.git
   cd spider-blacklist
   ```

3. **Create a New Branch**  
   It's best to create a new branch for your changes:

   ```
   git checkout -b add-your-domain
   ```

4. **Add the Domain**  
   Open the `blacklist.txt` file and add the domain you wish to blacklist. Please ensure you add one domain per line.

5. **Commit Your Changes**  
   After adding the domain, commit the changes with a meaningful commit message:

   ```
   git add blacklist.txt
   git commit -m "Add example.com to blacklist"
   ```

6. **Push Your Changes**  
   Push the changes back to your GitHub repository:

   ```
   git push origin add-your-domain
   ```

7. **Create a Pull Request**  
   Go to your repository on GitHub and click on 'Compare & pull request'. Submit the pull request with a clear title and description of why the domain should be blacklisted.

### Guidelines for Blacklisting Domains

- **Sensitive Content**: Domains that primarily host sensitive content that should not be tracked.
- **Privacy Concerns**: Sites where privacy is paramount and user tracking is explicitly discouraged.
- **User Requests**: Domains requested by users to be added to the blacklist due to personal data concerns.

### Review Process

Our team reviews pull requests regularly. Once reviewed, if the domain meets our criteria, it will be merged into the main blacklist. The changes will take effect the next time the Spider extension syncs with the repository.

## Feedback

If you have suggestions or feedback about the Blacklist or the Spider extension, please open an issue in this repository. We appreciate your input and are committed to improving this community-driven project.

Thank you for contributing to the Spider Community Blacklist!
