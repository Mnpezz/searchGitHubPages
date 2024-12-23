# GitHub Pages Directory

A simple web application that helps you discover GitHub Pages websites. This tool searches through GitHub repositories and displays those that have GitHub Pages enabled or are likely to have associated websites.

## Features

- 🔍 Real-time search functionality
- 📱 Responsive design
- 🏷️ Shows repository tags and topics
- ⭐ Displays repository star count
- 👤 Shows repository owner
- 📄 Indicates if GitHub Pages is enabled

## Usage

1. Visit the website
2. Type in the search box to find GitHub Pages
3. Results will update automatically as you type
4. Click on any result to visit their GitHub Pages website

## Search Tips

- Search by repository name
- Search by topic
- Search by description
- Search by README content

## Technical Details

- Uses the GitHub API to search repositories
- Filters results to show repositories that:
  - Have GitHub Pages enabled
  - Use github.io domains
  - Have documentation or website-related topics
- Limited to 100 results per search (GitHub API limitation)
- Has rate limiting (60 requests per hour for unauthenticated users)

## Local Development

1. Clone the repository: 
bash
git clone https://github.com/yourusername/github-pages-directory.git


2. Open `index.html` in your web browser

No build process or dependencies required!

## Limitations

- GitHub API rate limits (60 requests per hour for unauthenticated users)
- Only shows public repositories
- Limited to 100 results per search
- May not detect all GitHub Pages websites

## Contributing

Feel free to open issues or submit pull requests with improvements!

## License

MIT License - feel free to use this project however you'd like!