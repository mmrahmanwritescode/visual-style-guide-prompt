# Event Hive Sign-In Page - Visual Style Guide

## Overview
This document outlines the visual design system and style guide for the Event Hive sign-in page, built with Bootstrap 5 and custom CSS styling.

## Brand Identity

### Logo & Brand Name
- **Brand Name**: "Event Hive"
- **Typography**: "Event" in regular weight, "Hive" highlighted in brand purple
- **Brand Color**: `#7848F4` (Primary Purple)

## Color Palette

### Primary Colors
- **Brand Purple**: `#7848F4`
- **Purple Hover**: `#6230e0`
- **Background**: `#F8F8FA` (Light gray)
- **Text Primary**: Default black
- **Text Muted**: `#687C94` (Gray-blue)

### Accent Colors
- **White**: `#FFFFFF`
- **Border/Divider**: Default gray
- **Glassmorphism**: `rgba(255, 255, 255, 0.2-0.35)`

## Typography

### Font Family
- **Primary Font**: Inter (Google Fonts)
- **Weights Used**: 400 (Regular), 500 (Medium), 600 (Semi-bold), 700 (Bold)
- **Fallback**: sans-serif

### Heading Hierarchy
- **Brand Title (H1)**: `.h4` class, `fw-bold`
- **Page Title (H2)**: `fs-2`, `fw-bold`
- **Form Labels**: `fs-6`, `fw-medium`

## Layout Structure

### Container Widths
- **Brand Title Container**: `118px` (centered)
- **Main Heading Container**: `338px` (centered)
- **Form Container**: `578px` (left-aligned)

### Grid System
- **Left Column**: `col-md-7` (Form section)
- **Right Column**: `col-md-5` (Hero image section)
- **Responsive**: Collapses to single column on mobile

## Component Styles

### Form Elements

#### Input Fields
- **Padding**: `0.75rem 1.25rem`
- **Border Radius**: `rounded-3`
- **Placeholder Color**: `#687C94`
- **Focus State**: 
  - Border: `#7848F4`
  - Shadow: `rgba(120, 72, 244, 0.25)`

#### Labels
- **Style**: `fw-medium fs-6`
- **Transform**: Uppercase for primary labels
- **Color**: Default text color

### Buttons

#### Primary Button (Sign In)
- **Background**: `#7848F4`
- **Hover**: `#6230e0`
- **Padding**: `12px 24px`
- **Font Size**: `16px`
- **Border Radius**: `rounded-3`
- **Font Weight**: `fw-semibold`
- **Width**: `w-100` (full width of container)

#### Secondary Button (Google Sign-In)
- **Background**: White
- **Border**: Light gray
- **Padding**: Vertical `py-3`
- **Icon**: Google SVG icon
- **Layout**: Flexbox with gap

#### Glassmorphism Button (Sign Up - Right Panel)
- **Background**: `rgba(255, 255, 255, 0.2)`
- **Border**: `1px solid rgba(255, 255, 255, 0.3)`
- **Backdrop Filter**: `blur(10px)`
- **Shadow**: `0 4px 15px rgba(0, 0, 0, 0.1)`
- **Hover Effect**: 
  - Background: `rgba(255, 255, 255, 0.35)`
  - Enhanced shadow: `0 6px 20px rgba(0, 0, 0, 0.15)`
- **Transition**: `all 0.3s ease`

### Links
- **Color**: `#7848F4` (Brand purple)
- **Text Decoration**: None
- **Font Weight**: `fw-medium`

## Spacing & Layout

### Margins & Padding
- **Section Padding**: `p-5` on containers
- **Form Spacing**: `mb-4` between form groups
- **Component Spacing**: `my-5` for dividers
- **Button Spacing**: `mt-4` for secondary actions

### Responsive Behavior
- **Desktop**: Two-column layout with hero image
- **Mobile**: Single column, hero section hidden (`d-none d-md-block`)

## Hero Section (Right Panel)

### Background
- **Image**: `right.png` (cover positioning)
- **Overlay**: `rgba(0,0,0,0.3)` for text readability
- **Layout**: Centered flex column

### Content
- **Heading**: `fs-1 fw-bold` in white
- **Description**: `fs-5` in white
- **CTA Button**: Glassmorphism style (see button section)

## Visual Effects

### Glassmorphism
- **Backdrop Blur**: `blur(10px)`
- **Semi-transparent backgrounds**: Various opacity levels
- **Subtle shadows**: Multiple shadow layers for depth

### Transitions
- **Button Hovers**: `0.3s ease`
- **Focus States**: Smooth color transitions
- **Interactive Elements**: Consistent timing

## Accessibility Features

### Focus States
- **Custom Focus**: Purple border with matching shadow
- **Keyboard Navigation**: All interactive elements accessible

### Color Contrast
- **Text on Background**: High contrast maintained
- **Button States**: Clear visual feedback

## Bootstrap 5 Integration

### Utility Classes Used
- **Display**: `d-flex`, `d-none`, `d-md-block`
- **Flexbox**: `align-items-center`, `justify-content-center`
- **Spacing**: `p-*`, `m-*`, `py-*`, `px-*`
- **Typography**: `fs-*`, `fw-*`, `text-*`
- **Borders**: `rounded-*`, `border`
- **Sizing**: `w-100`, `min-vh-100`

### Custom Overrides
- **Primary Button Colors**: Override Bootstrap defaults
- **Form Focus States**: Custom purple theme
- **Typography**: Inter font family integration

## File Structure
```
├── index.html (Main HTML structure)
├── style.css (Custom styling - can be integrated into HTML)
├── right.png (Hero background image)
└── Bootstrap 5.3.2 CDN (External dependency)
```

## Design Principles
1. **Consistent Spacing**: Uniform margin/padding system
2. **Typography Hierarchy**: Clear size and weight differentiation
3. **Color Consistency**: Limited, purposeful color palette
4. **Progressive Enhancement**: Mobile-first responsive design
5. **Brand Cohesion**: Purple accent color throughout interface
6. **Modern Aesthetics**: Glassmorphism and subtle shadows
7. **User Experience**: Clear visual feedback and intuitive layout