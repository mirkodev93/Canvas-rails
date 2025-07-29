# Canvas Rails

Canvas is a modern learning management system (LMS) built with Ruby on Rails. It provides a comprehensive platform for educational institutions to manage courses, assignments, grades, and student interactions.

## Features

- **Course Management**: Create and manage courses with rich content
- **Assignment System**: Support for various assignment types and grading
- **Gradebook**: Comprehensive grading and assessment tools
- **Communication**: Built-in messaging and discussion forums
- **File Management**: Secure file upload and sharing capabilities
- **Mobile Support**: Responsive design for mobile devices
- **API Integration**: RESTful APIs and GraphQL support
- **LTI Integration**: Learning Tools Interoperability support
- **Multi-tenant Architecture**: Support for multiple institutions

## Technology Stack

- **Backend**: Ruby on Rails
- **Database**: PostgreSQL
- **Frontend**: Modern JavaScript with React components
- **Testing**: RSpec for Ruby, Jest for JavaScript
- **Styling**: CSS with responsive design
- **Authentication**: Multiple authentication methods
- **File Storage**: Amazon S3 integration

## Getting Started

### Prerequisites

- Ruby (version specified in `.ruby-version`)
- PostgreSQL
- Node.js and npm
- Redis (for caching and sessions)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd canvas-rails
   ```

2. Install Ruby dependencies:
   ```bash
   bundle install
   ```

3. Install JavaScript dependencies:
   ```bash
   npm install
   ```

4. Set up the database:
   ```bash
   bundle exec rake db:create
   bundle exec rake db:migrate
   ```

5. Start the development server:
   ```bash
   bundle exec rails server
   ```

## Development

### Running Tests

```bash
# Ruby tests
bundle exec rspec

# JavaScript tests
npm test
```

### Code Quality

The project uses RuboCop for Ruby code style enforcement and ESLint for JavaScript.

## Contributing

Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

## License

This project is licensed under the terms specified in the [COPYRIGHT](COPYRIGHT) file.

## Support

For support and documentation, please refer to the [Canvas Documentation](https://canvas.instructure.com/doc/).

## Architecture

Canvas follows a modular architecture with:
- **Models**: ActiveRecord models for data management
- **Controllers**: RESTful controllers handling HTTP requests
- **Services**: Business logic encapsulation
- **GraphQL**: Modern API for frontend communication
- **Gems**: Custom Canvas gems for specific functionality

The application supports multiple deployment environments and can be scaled horizontally for high-traffic educational institutions.
