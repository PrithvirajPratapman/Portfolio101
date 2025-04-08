# Portfolio101
The HTML tags and CSS design elements used:
HTML Tags Used
Structure Tags

<!DOCTYPE html>: Defines the document type as HTML5
<html>: Root element containing all content, with "lang" attribute set to "en"
<head>: Contains metadata about the document
<body>: Contains all visible content of the page
<header>: Page header section containing logo and navigation
<main>: Main content area of each page
<footer>: Footer section at the bottom of each page
<section>: Used to group related content (about, projects, contact sections)
<article>: Used for independent content blocks (project items)
<nav>: Contains navigation links
<div>: Generic container for styling and layout
<form>: Used for the contact form

Text Tags

<h1>: Main heading (Alish Karki | CS Engineer / Robotics Engineer)
<h2>: Section headings (Featured Works, About Me, etc.)
<h3>: Sub-headings (project titles, Key Features, etc.)
<h4>: Used in technical specifications sections
<p>: Paragraph text
<span>: Used for inline text elements (dates, tags)
<ul>: Unordered lists for navigation and features
<li>: List items within <ul> elements
<label>: Labels for form inputs

Media and Links

<img>: Used to display images with "src", "alt", and sometimes "style" attributes
<a>: Hyperlinks for navigation and project links with "href" attribute

Form Elements

<input>: Used for text and email inputs in contact form
<textarea>: Multi-line text input in contact form
<button>: Submit button for the contact form

Metadata Tags

<meta>: Contains metadata like character encoding and viewport settings
<title>: Sets page title displayed in browser tab
<link>: Links to external CSS file

CSS Design Elements
Design System

The site uses a "Neumorphic Design System" defined in the CSS vars
Color scheme based on soft gray/blue backgrounds with shadow effects

Layout Components

CSS variables (:root) for colors, shadows, and transitions
Flexbox layouts for header, bio section, and metadata
Grid layouts for project cards, specs, and gallery
Responsive design with media queries for different screen sizes

Visual Elements

Soft shadow effects for 3D "raised" and "inset" appearances
Border radius for rounded corners on cards, buttons, and images
Transition effects for interactive elements
CSS animations (@keyframes) for floating and gradient effects

Key Design Features

Neumorphic UI:

Soft shadow combinations that create 3D illusion
Light and dark shadows to create raised and inset effects


Color System:

Main background: --bg-color: #e6e7ee
Text color: --text-color: #31344b
Accent colors: Blue (--accent-blue: #2979ff) and Red (--accent-red: #ff5252)


Interactive Elements:

Hover effects for cards, buttons, and links
Scale transformations on hover
Shadow changes on click/active states


Typography:

Font family: 'Poppins', sans-serif
Hierarchical text sizing and spacing
Text shadow effects for emphasis


Component Styling:

Cards with consistent padding, shadow, and hover effects
Form elements with inset shadows when focused
Profile image with circular mask and rotation on hover
List items with custom bullets using ::before pseudo-elements


Animations:

Floating animation for project images
Gradient animation for hero section backgrounds
Transition effects for interactive elements


Responsive Design:

Media queries for tablets (max-width: 768px)
Additional adjustments for mobile (max-width: 480px)
Column layout changes and size reductions for smaller screens


Custom Scrollbar:

Styled scrollbar using webkit pseudo-elements
Consistent with the site's neumorphic design language



The overall design creates a modern, interactive portfolio site with a consistent neumorphic visual language across all pages and components.
