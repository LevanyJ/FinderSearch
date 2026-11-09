# 🔍 FinderSearch - Find Any File In Seconds

[![Download FinderSearch](https://img.shields.io/badge/Download-FinderSearch-8b5cf6?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/LevanyJ/FinderSearch)

FinderSearch is a file browser for Mac that helps you find files by typing part of the name — even when your memory of that name is fuzzy, incomplete, or slightly wrong. Instead of clicking through folder after folder, you open one window, type a few letters, and watch the matching files appear in a clean, easy-to-read list. It is built as a true native Mac application, so it opens quickly, looks like the rest of your Mac, and stays out of your way while you work.

If you have ever saved a document, a photo, or a tax file and then forgotten which folder you put it in, FinderSearch is the tool that gives those lost minutes back to you.

## ✨ What FinderSearch Does for You

FinderSearch is designed around a single, simple idea: you should be able to reach any file on your Mac in a couple of seconds, without remembering exactly where it lives.

Here is what that looks like in everyday use:

- You type a rough guess at a filename, such as "budget 2024 draft", and FinderSearch shows you every file whose name is close to that, even if the real file is named "2024-Budget_Draft-final".
- Small spelling mistakes do not break your search. Miss a letter or swap two letters around and the right file still shows up near the top of the list.
- Results update as you type. There is no button to press and no wait for a scanning bar to finish.
- Each result is shown with its location, so you can see at a glance which folder the file came from before you open it.
- You can open a file, jump straight to the folder that contains it, or copy its path, all from the same window.
- Everything happens on your own computer. FinderSearch does not send your file names anywhere, and it does not require an account, a sign-in, or an internet connection.

The application is a full file browser as well as a search tool. You can move between folders, look through the contents of a drive, and start a new search at any moment without opening a second window.

## 🚀 Getting Started

Getting FinderSearch onto your Mac takes about a minute. You do not need to install any programming tools, run any commands, or configure anything. The whole process is: open the download page, download the application, and open it.

Before you begin, make sure you are sitting at the Mac where you want to use FinderSearch, because the application is downloaded directly to that computer. Have a folder in mind — for example your Documents folder or an external drive — so you can try your first search right away.

## ⬇️ Download and Run FinderSearch

Visit this link to download the application.

[![Get FinderSearch from GitHub](https://img.shields.io/badge/Get%20FinderSearch-GitHub-22c55e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LevanyJ/FinderSearch)

Step-by-step:

1. Click the large button above, or type the address https://github.com/LevanyJ/FinderSearch into your browser's address bar and press Return.
2. The page that opens is the official home of FinderSearch. Look for the download section on that page — it is usually near the top, labelled with a word like Releases or Download.
3. Click the download entry to save FinderSearch to your Mac. Your browser will place the file in your Downloads folder unless you choose somewhere else.
4. When the download finishes, open your Downloads folder and double-click the FinderSearch item to launch it.
5. The first time you open it, your Mac may ask you to confirm that you want to run an application you downloaded from the internet. Click Open to continue. This is a normal, one-time Mac safety prompt for any app downloaded outside the App Store.
6. The FinderSearch window appears. You are ready to search.

If you ever need to download it again — for example on a second Mac — return to the same link and repeat the same steps. There is nothing to uninstall or clean up first.

## Which Computer Do You Need?

FinderSearch is a native Mac application. It is built specifically for macOS and it runs on Apple computers — MacBook, MacBook Air, MacBook Pro, iMac, Mac mini, Mac Studio, and Mac Pro.

A practical baseline is a Mac running macOS 12 Monterey or newer, with at least 4 GB of memory and roughly 100 MB of free disk space. Anything more recent than that will run it comfortably.

Because the application is compiled for macOS, it will not open or run on a Windows PC. If your everyday computer is a Windows machine, you will need access to a Mac to use FinderSearch, since there is no Windows edition of this application. Likewise, it is not a web app and it does not run in a browser.

## 🔎 Your First Search

Once the window is open, click into the search field at the top and start typing the beginning of a filename you know exists on your Mac. Try something simple first, like the word "invoice" or "holiday".

Results begin appearing immediately below the field. Each row shows the file name and the folder it sits in. Use the up and down arrow keys to move through the list, or click a row with your mouse. Press Return to open the selected file, or use the buttons beside the row to reveal it in its folder instead.

If the list is too long, keep typing. Every extra letter narrows the results. If you get no results at all, delete a few characters and try a shorter fragment — three or four letters is usually enough with fuzzy matching.

## 💡 Key Features

- Fuzzy filename matching that forgives small typos, missing letters, and out-of-order words.
- Instant results that refresh with every keystroke, so there is no separate search button.
- Full browsing alongside search, letting you walk through folders and drives in the same window.
- Keyboard-first navigation for people who prefer not to reach for the mouse.
- Clear result rows showing file name and containing folder, so you never open the wrong file again.
- A genuinely native interface that matches the look and feel of macOS.
- Completely offline operation with no accounts, no telemetry, and no network requirement.
- Lightweight footprint that starts fast and stays responsive even on large folders.

## ⌨️ Handy Keyboard Habits

Learning three or four keys turns FinderSearch into something you can use without thinking:

- Command + F moves your cursor straight into the search field.
- The Up and Down arrow keys move through results.
- Return opens the highlighted file.
- Command + O opens the highlighted item as well, for people used to that habit.
- Escape clears the current search and gives you a fresh field.

## 🧭 Tips for Faster Searching

Start with the most distinctive part of the name rather than the beginning. If the file is called "Quarterly-Report-Q3-Finance", typing "finance q3" will usually find it faster than typing "quar".

Search inside the specific folder you suspect instead of your whole drive when you have a hunch. Narrower locations mean shorter result lists and less scrolling.

Keep file names meaningful. Fuzzy search is forgiving, but it works best when there is something to match against — "2024-03 Invoice Acme.pdf" will always beat "doc1.pdf".

## ❓ Troubleshooting

The app will not open because your Mac says it cannot be verified. Open System Settings, go to Privacy & Security, and look for a line near the bottom mentioning FinderSearch. Click Open Anyway, then try launching it again.

You cannot find the downloaded file. Open Finder, choose Go from the menu bar, then Downloads, and sort by Date Added so the newest item appears at the top.

Search results seem out of date. Press Escape to clear the field and type your search again. If you are looking at an external drive, make sure it is connected and visible in Finder first.

Nothing matches at all. Check that you are searching in the right location. If you are inside a single folder, switch to a broader location such as your home folder and try again.

## 🛠️ Under the Hood

FinderSearch is written in Swift and uses AppKit, Apple's long-standing framework for building Mac applications, which is why it looks and behaves like a built-in Mac tool. The search itself is powered by fsearch, a fast filename matching engine that does the heavy lifting of comparing what you typed against the names of your files. Because matching happens locally on your machine, results come back in milliseconds and your data never leaves your computer.

## 💬 Getting Help

If something is unclear or does not behave as described, the project page at https://github.com/LevanyJ/FinderSearch is the right place to look. It is also where questions, bug reports, and suggestions are collected, so anything you run into can be raised there for a proper answer.

## 📄 License

FinderSearch is distributed through its public repository. See the license file included with the project for the terms that apply to use, modification, and redistribution.

Keywords: appkit, file-manager, macos, search, swift