# Proposal for React component library for Thrive Design System

## Available Options

There are several popular React component libraries that are widely used by developers. However, it's important to consider specific project requirements and evaluate whether any of these component library ecosystem meets our needs.

**Main 3 options in my opinion we need to consider:**

Mantine, Ant Design and MaterialUI are all popular UI component libraries that provide pre-built components and styles for building user interfaces in web applications. Each library has its own unique features and design principles, so the choice between them depends on our specific requirements and preferences.

---

[Mantine](http://mantine.dev/) is a modern library focused on providing an excellent user and developer experience. Development began in January 2021, and the 1.0 version was published on May 3rd, 2021. Since then, it has seen over 100 releases.

**Key Features:**

- **Performance and Accessibility**: Mantine emphasizes performance and accessibility. Its smaller bundle size compared to other libraries can lead to faster loading times. It offers a set of components and hooks for building responsive and accessible interfaces.
- **TypeScript Support**: It provides TypeScript support out of the box, which can be beneficial for type-safe development.
- **[Components](https://mantine.dev/core/button/)**: the core components library is extensive and includes niche components like color pickers, date-range pickers, and timelines. With over 100 different components, you'll rarely need to create your own. Each component supports style overriding for internal elements with classes or inline styles.
- **[Theming & Customization](https://mantine.dev/theming/theme-object/)**: It has a clean and customizable design, allowing you to tweak the styles to fit your project's needs. Mantine's theming is an object that you can subscribe to from anywhere using context and extend with any number of additional colors, fonts, shadows, and so on. All components support both light and dark themes out of the box.
- **[Documentation & Support](https://mantine.dev/pages/about/)**: Mantine is built and maintained by Vitaly Rtishchev and over 150 other contributors. Most new features and components/hooks are added to the library based on feedback from the community. You can participate in new features discussions on [GitHub](https://github.com/mantinedev/mantine/discussions) or [Discord](https://discord.com/invite/wbH82zuWMN). The documentation is comprehensive, covering everything from basic usage to advanced topics, with plenty of examples and tutorials to help you get started.
- **Stats**:

  | Stars ⭐️                                      | Issues 🐞                                           | Weekly NPM ⬇️                                        | StackOverflow ❓                                         | Components | Origin |
  | ---------------------------------------------- | --------------------------------------------------- | ---------------------------------------------------- | -------------------------------------------------------- | ---------- | ------ |
  | [16.4k](https://github.com/mantinedev/mantine) | [107](https://github.com/mantinedev/mantine/issues) | [58.2k](https://www.npmjs.com/package/@mantine/core) | [69](https://stackoverflow.com/questions/tagged/mantine) | 120+       | Vitaly |

- <details>
   <summary><strong>📜 Overview of components grouped by category</strong></summary>

  - **Layout**
    - AppShell
    - AspectRatio
    - Center
    - Container
    - Flex
    - Grid
    - Group
    - MediaQuery
    - SimpleGrid
    - Space
    - Stack
  - **Buttons**
    - ActionIcon
    - Button
    - CloseButton
    - CopyButton
    - FileButton
    - UnstyledButton
  - **Inputs**
    - Autocomplete
    - Checkbox
    - Chip
    - ColorInput
    - ColorPicker
    - FileInput
    - Input
    - JsonInput
    - MultiSelect
    - NativeSelect
    - NumberInput
    - PasswordInput
    - PinInput
    - Radio
    - Rating
    - SegmentedControl
    - Select
    - Slider
    - Switch
    - Textarea
    - TextInput
    - TransferList
  - **Navigation**
    - Anchor
    - Breadcrumbs
    - Burger
    - NavLink
    - Pagination
    - Stepper
    - Tabs
  - **Data display**
    - Accordion
    - Avatar
    - BackgroundImage
    - Badge
    - Card
    - ColorSwatch
    - Image
    - Indicator
    - Kbd
    - Spoiler
    - ThemeIcon
    - Timeline
  - **Overlays**
    - Affix
    - Dialog
    - Drawer
    - HoverCard
    - LoadingOverlay
    - Menu
    - Modal
    - Overlay
    - Popover
    - Tooltip
  - **Typography**
    - Blockquote
    - Code
    - Highlight
    - List
    - Mark
    - Table
    - Text
    - Title
    - TypographyStylesProvider
  - **Feedback**
    - Alert
    - Loader
    - Notification
    - Progress
    - RingProgress
    - Skeleton
  - **Miscellaneous**
    - Box
    - Collapse
    - Divider
    - FocusTrap
    - Paper
    - Portal
    - ScrollArea
    - Transition
    </details>

**Cons**:

---

**[Ant Design](https://ant.design/)** is a popular, comprehensive design system and user interface library for building enterprise-level web applications. Originating from Alibaba, it's based primarily on the React JavaScript library and provides a vast range of pre-designed components.

**Key Features:**

- **Design System**: The design system of Ant Design is well-defined and consistent, ensuring visual coherence across your project. It also provides powerful layout and grid systems, making it suitable for building complex user interfaces.
- **Internationalization**: With built-in support for internationalization, Ant Design allows you to easily translate and localize your application to various languages and regions.
- **[Components](https://ant.design/components/overview/)**: It offers a vast range of pre-designed components such as forms, buttons, tables, and modals. This makes it possible to build complex and consistent user interfaces with a faster development cycle. In total, it provides more than 70 components that serve as the building blocks for enterprise applications. For components that fall outside of the Ant Design specification, they recommend using other third-party React libraries, such as the [React Hooks Library](https://github.com/alibaba/hooks).
- **[Theming & Customization](https://ant.design/docs/react/customize-theme)**: It allows for the customization of design tokens to meet diverse UI requirements from business or brand perspectives, including primary color, border radius, border color, etc. Both Less and Sass are supported for styling customization.
- **[Documentation & Support](https://ant.design/docs/react/introduce)**: It is well-documented and supported, with guides covering everything from installation to components to styling. It also has strong community support and active development, which is beneficial for long-term project stability.
- **Stats**:

  | Stars ⭐️                                         | Issues 🐞                                              | Weekly NPM ⬇️                              | StackOverflow ❓                                        | Components | Origin    |
  | ------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------- | ---------- | --------- |
  | [83.6k](https://github.com/ant-design/ant-design) | [908](https://github.com/ant-design/ant-design/issues) | [640k](https://www.npmjs.com/package/antd) | [4.7k](https://stackoverflow.com/questions/tagged/antd) | 70+        | Ant Group |

- <details>
   <summary><strong>📜 <a href="https://ant.design/components/overview/" rel="noopener noreferrer">Overview</a> of components grouped by category</strong></summary>

  - **General**
    - Button
    - Icon
    - Typography
  - **Layout**
    - Divider
    - Grid
    - Layout
    - Space
  - **Navigation**
    - Anchor
    - Breadcrumb
    - Dropdown
    - Menu
    - Pagination
    - Steps
  - **Data Entry**
    - AutoComplete
    - Cascader
    - Checkbox
    - ColorPickerNew
    - DatePicker
    - Form
    - Input
    - InputNumber
    - Mentions
    - Radio
    - Rate
    - Select
    - Slider
    - Switch
    - TimePicker
    - Transfer
    - TreeSelect
    - Upload
  - **Data Display**
    - Avatar
    - Badge
    - Calendar
    - Card
    - Carousel
    - Collapse
    - Descriptions
    - Empty
    - Image
    - List
    - Popover
    - QRCode
    - Segmented
    - Statistic
    - Table
    - Tabs
    - Tag
    - Timeline
    - Tooltip
    - Tour
    - Tree
  - **Feedback**
    - Alert
    - Drawer
    - Message
    - Modal
    - Notification
    - Popconfirm
    - Progress
    - Result
    - Skeleton
    - Spin
  - **Other**
    - Affix
    - App
    - ConfigProvider
    - FloatButton
    - Watermark
    </details>

**Cons**:

---

**[Material-UI](https://mui.com/)** Material-UI is a popular and highly customizable component library that implements Google's Material Design guidelines.

- **Design System**: It is based on Google's Material Design guidelines, which provide a clean and modern look.
- **Community and Resources**: Material-UI boasts a large and active community, with an abundance of resources and third-party integrations available. This makes it easy to find support and examples.
- **[Components](https://mui.com/material-ui/)**: It offers a comprehensive set of pre-designed UI components such as app bars, time pickers, buttons, dropdowns, and modals. These components facilitate the building of responsive and accessible web interfaces.
- **[Theming & Customization](https://mui.com/material-ui/customization/theming/)**: It provides robust theming options based on Styled Components. This allows for systematic customization of Material Design to better reflect your product’s brand. It's an efficient way to apply consistent design across your app and make global design changes with minimal effort.
- **[Documentation & Support](https://mui.com/material-ui/getting-started/support/)**: It is well-documented and supported. Its documentation covers everything from installation to components to styling, and guides for implementing utilities like server-side rendering and localization. For additional support, Material-UI has a dedicated Discord channel, StackOverflow tags, and GitHub issues for troubleshooting and discussions.
- **Stats**:

  | Stars ⭐️                                       | Issues 🐞                                         | Weekly NPM ⬇️                                       | StackOverflow ❓                                             | Components | Origin |
  | ----------------------------------------------- | ------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------ | ---------- | ------ |
  | [83.7k](https://github.com/mui-org/material-ui) | [1.3K](https://github.com/mui/material-ui/issues) | [1.7M](https://www.npmjs.com/package/@mui/material) | [1M](https://stackoverflow.com/questions/tagged/material-ui) | 100+       | Google |

- <details>
   <summary><strong>📜 <a href="https://mui.com/material-ui/" rel="noopener noreferrer">Overview</a> of components grouped by category</strong></summary>

  - **Inputs**
    - Autocomplete
    - Button
    - Button
    - Group
    - Checkbox
    - Floating Action Button
    - Radio Group
    - Rating
    - Select
    - Slider
    - Switch
    - Text
    - Field
    - Transfer List
    - Toggle Button
  - **Data display**
    - Avatar
    - Badge
    - Chip
    - Divider
    - Icons
    - Material Icons
    - List
    - Table
    - Tooltip
    - Typography
  - **Feedback**
    - Alert
    - Backdrop
    - Dialog
    - Progress
    - Skeleton
    - Snackbar
  - **Surfaces**
    - Accordion
    - App
    - Bar
    - Card
    - Paper
  - **Navigation**
    - Bottom Navigation
    - Breadcrumbs
    - Drawer
    - Link
    - Menu
    - Pagination
    - Speed Dial
    - Stepper
    - Tabs
  - **Layout**
    - Box
    - Container
    - Grid
    - Grid
    - v2
    - Stack
    - Image List
    - Hidden
  - **Utils**
    - Click-Away Listener
    - CSS Baseline
    - Modal
    - No SSR
    - Popover
    - Popper
    - Portal
    - Textarea Autosize
    - Transitions
    - useMediaQuery
  - **MUI X**
    - Data Grid
    - Date & Time Pickers
  - **Lab**
    - Masonry
    - Timeline
    - Tree
    - View
    </details>

**Cons**:

---

Additional info about these 3 libraries:

- https://mantine.dev/pages/about/
- https://ant.design/docs/react/introduce
- https://mui.com/about/

**Minimum required packages to install with unpacked sizes:**

- Mantine: `@mantine/core` (6.22 MB), `@mantine/hooks` (562 kB), `@emotion/react` (584 kB).
- Ant Design: `antd` (51.8 MB).
- Material UO: `@mui/material` (10.1 MB), `@emotion/styled` (177 kB), `@emotion/react` (584 kB).

In summary, Mantine, Ant Design, and MaterialUI are all great options for building web interfaces. MaterialUI is well-suited for general-purpose applications, Mantine focuses on performance and developer experience, while Ant Design is popular for enterprise-level applications with a distinctive design system.

---

**Other alternatives popular ones:** (We are less likely going to use/choose one of those options below)

- [Chakra UI](https://chakra-ui.com/): Chakra UI is a simple and accessible component library that aims to provide a delightful developer experience. It offers a set of customizable components and a design system that promotes building accessible and responsive interfaces.

- [Semantic UI React](https://react.semantic-ui.com/): Semantic UI React is a React integration of the Semantic UI library. It provides a wide variety of components with semantic class names, making it easy to build visually appealing and user-friendly interfaces.

- [React Bootstrap](https://react-bootstrap.netlify.app/): React Bootstrap is a React implementation of the popular Bootstrap framework. It provides a collection of reusable components that follow Bootstrap's responsive design principles.

- [Blueprint](https://blueprintjs.com/): Blueprint is a UI toolkit for building complex, data-dense web interfaces. It offers a collection of customizable components, including tables, forms, and charts, designed specifically for data-driven applications.

- [Evergreen](https://evergreen.segment.com/): Evergreen is a UI library designed for building scalable and maintainable applications. It provides a set of robust and accessible components that can be easily combined to create complex user interfaces.

- [Grommet](https://v2.grommet.io/): Grommet is a component library designed for creating responsive and accessible interfaces. It offers a collection of pre-built components and a theming system that allows for easy customization.

## Table of non-exhaustive components needed for Thrive Design System

Based on:

- [Our Rhino Design System Figma](https://www.figma.com/file/zqw7kwjn9iR7ygoDnAq62P/Rhino?type=design&node-id=1051-5023&t=GqZsc0cvWOSz9MXQ-0)
- [Rhino Design System Asana Board](https://app.asana.com/0/1202653124846172/board)

| Component Name           | Mantine                                                      | AntD                                                   | MaterialUI                                           |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------ | ---------------------------------------------------- |
| Accordion                | [✅](https://mantine.dev/core/accordion)                     | [✅](https://ant.design/components/collapse)           | [✅](https://mui.com/material-ui/react-accordion)    |
| Blankslate / Empty       | 🚫                                                           | [✅](https://ant.design/components/empty)              | 🚫                                                   |
| Breadcrumbs              | [✅](https://mantine.dev/core/breadcrumbs)                   | [✅](https://ant.design/components/breadcrumb)         | [✅](https://mui.com/material-ui/react-breadcrumbs)  |
| Button                   | [✅](https://mantine.dev/core/button)                        | [✅](https://ant.design/components/button)             | [✅](https://mui.com/material-ui/react-button)       |
| Checkbox                 | [✅](https://mantine.dev/core/checkbox)                      | [✅](https://ant.design/components/checkbox)           | [✅](https://mui.com/material-ui/react-checkbox)     |
| Layout / Containers      | [✅](https://mantine.dev/core/container)                     | [✅](https://ant.design/components/layout)             | [✅](https://mui.com/material-ui/react-grid)         |
| Modal                    | [✅](https://mantine.dev/core/modal)                         | [✅](https://ant.design/components/modal)              | [✅](https://mui.com/material-ui/react-modal)        |
| Dialog                   | [✅](https://mantine.dev/core/dialog)                        | [✅](https://ant.design/components/modal)              | [✅](https://mui.com/material-ui/react-dialog)       |
| Form Group               | [✅](https://mantine.dev/core/input/#inputwrapper-component) | [✅](https://ant.design/components/form)               | [✅](https://mui.com/material-ui/react-text-field/)  |
| Menu / Menu Item         | [✅](https://mantine.dev/core/menu)                          | [✅](https://ant.design/components/menu)               | [✅](https://mui.com/material-ui/react-menu)         |
| Navigation               | [✅](https://mantine.dev/core/app-shell/)                    | [✅](https://ant.design/components/layout#layoutsider) | [🚫](https://mui.com/material-ui/react-drawer)       |
| Tag / Pill / Chip        | [✅](https://mantine.dev/core/chip)                          | [✅](https://ant.design/components/tag)                | [✅](https://mui.com/material-ui/react-chip)         |
| Radio Buttons            | [✅](https://mantine.dev/core/radio)                         | [✅](https://ant.design/components/radio)              | [✅](https://mui.com/material-ui/react-radio-button) |
| Typeahead / Autocomplete | [✅](https://mantine.dev/core/select)                        | [✅](https://ant.design/components/select)             | [✅](https://mui.com/material-ui/react-select)       |
| Select / MultiSelect     | [✅](https://mantine.dev/core/autocomplete)                  | [✅](https://ant.design/components/auto-complete)      | [✅](https://mui.com/material-ui/react-autocomplete) |
| Spacing                  | [✅](https://mantine.dev/core/spacing)                       | [✅](https://ant.design/components/space)              | [✅](https://mui.com/material-ui/react-spacing)      |
| Stepper                  | [✅](https://mantine.dev/core/stepper)                       | [✅](https://ant.design/components/steps)              | [✅](https://mui.com/material-ui/react-stepper)      |
| Table                    | [✅](https://mantine.dev/core/table)                         | [✅](https://ant.design/components/table)              | [✅](https://mui.com/material-ui/react-table)        |
| Tabs                     | [✅](https://mantine.dev/core/tabs)                          | [✅](https://ant.design/components/tabs)               | [✅](https://mui.com/material-ui/react-tabs)         |
| Textfield                | [✅](https://mantine.dev/core/text-input)                    | [✅](https://ant.design/components/input)              | [✅](https://mui.com/material-ui/react-textfields)   |
| Toast / Notification     | [✅](https://mantine.dev/core/notification)                  | [✅](https://ant.design/components/notification)       | [✅](https://mui.com/material-ui/react-snackbar)     |
| Typography / Title       | [✅](https://mantine.dev/core/text)                          | [✅](https://ant.design/components/typography)         | [✅](https://mui.com/material-ui/react-typography)   |
| List                     | [✅](https://mantine.dev/core/list)                          | [✅](https://ant.design/components/list)               | [✅](https://mui.com/material-ui/react-list)         |

✅ - This component is available in the library. `Control / ⌘ + Click` the link to view it.

🚫 - This component is not available in the library.
