PETERSEN BID — PRIVATE PAGES FOR CWENARGC.COM
==============================================

What this is
  Five passcode-locked pages. The content of each page is encrypted inside the file
  (AES-256, key derived from the passcode). Without the passcode the files are unreadable,
  even to someone who downloads them from the server.

  index.html       menu of the four files
  win-plan.html    internal win plan
  spec-sheet.html  materials spec & quantity takeoff
  worksheet.html   estimate worksheet (numbers save in each person's browser)
  proposal.html    customer proposal (prices fill in from the worksheet)

Passcode
  Bobby8171   (shared with Bob and whoever else should have access)

How to publish
  Upload the whole "g7k2-pm-4x9q" folder to the website's root, next to index.html for the site.
  The folder name is deliberately random so the address can't be guessed. Nothing on the
  site links to it, and every page tells search engines not to index it.
  The link is then:   https://cwenargc.com/g7k2-pm-4x9q/
  It must be served over https:// — the lock uses the browser's built-in encryption,
  which browsers only allow on secure pages. Nothing else to configure; no server code.

How it behaves
  First visit asks for the passcode. "Keep me signed in on this device" means the person
  won't be asked again on that computer or phone. "Sign out on this device" is on the menu page.
  Each page prints normally (File > Print > Save as PDF) once it is open.

The worksheet and the proposal
  The worksheet saves automatically in the browser of whoever types in it. The proposal reads
  those numbers in the same browser. To hand numbers to someone else: click "Save my numbers
  to a file" in the worksheet, send them the file, they click "Load numbers from a file".

To change the passcode or update a page
  Edit the source files in the design workspace and re-publish; the five files here are
  replaced. Changing the passcode re-encrypts all five.
