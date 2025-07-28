---
mode: "edit"
tools: ["filesystem"]
description: "Generate React component with TypeScript and testing"
---

# Create React Component

Generate a complete React component with the following requirements:

## Component Details
- **Name**: ${input:componentName:Enter component name (PascalCase)}
- **Props**: ${input:props:List the props this component needs}
- **Styling**: ${input:styling:CSS modules, styled-components, or Tailwind?}

## Requirements
- TypeScript with proper interfaces
- PropTypes for runtime validation (if needed)
- Responsive design considerations
- Accessibility attributes (ARIA labels, semantic HTML)
- Unit tests with React Testing Library
- Storybook story (if Storybook is configured)

## File Structure
Create the following files:
- ComponentName.tsx - Main component
- ComponentName.module.css - Styles (if CSS modules)
- ComponentName.test.tsx - Unit tests
- ComponentName.stories.tsx - Storybook story (optional)
- index.ts - Export file

Reference existing patterns from similar components in the codebase.
Follow the project's established patterns for state management and styling.
