# TrustyHash - A Trustable Hash Calculator

TrustyHash is a small [client-side](https://unhosted.org/) web application that
computes SHA-256 hash values on both local files and on remote URLs, with a
strong emphasis on a process that will allow you to trust the results. Works
offline!

TrustyHash homepage: https://github.com/sprin/TrustyHash

[Use it here](https://sprin.github.io/TrustyHash/)

## How is this useful?

Integrity: "We have in hand the same set of sequences of bits that came into
existence when the object was created" - [Lynch](http://www.clir.org/pubs/reports/pub92/lynch.html)

"Friends don't let friends use unverified downloads."

This fills a need for a verifiable, web-based hash calculator written in free
JavaScript. If you already use the command-line hash utilities on your
system, you should continue to use those. This is targeted towards users who do
not have or are unable to use the hash utilities on their local systems. While
universal command-line-literacy is a good goal, the concepts of file integrity and
authenticity and the ability to use tools for verification are perhaps more
fundamental.

Integrity is the first link in secure systems, and key to determining
authenticity. If we trust the association between an author and the hash value
of a file they created, perhaps because we trust them and they gave us the
hash in person, we can authenticate whether a file we believe to be the same
really did come from them. We can achieve the same result if the author had
used a signing key, and signed and distributed a hash value along with the
file, and we could trust the association between a particular key and the
author - albeit with somewhat more complexity and caveats (eg, has the signing
key been kept private?).

In a few words, this tool aims to enable verification of integrity and
authenticity claims in an accessible way that depends only on a trusted hash
value and the correctness and integrity of the TrustyHash app and the browser
it executes in. See the section "Trust" below for recommendations on
how to verify integrity of this application.

## Usage

Local files can be opened from a file select dialog, or dragged into the "drop
area". Remote URLs can be entered, and if the remote server allows cross-origin
GET requests via
[CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS),
the file will be downloaded to the browser, with the option of saving locally.

It's recommended to save the application, verify the integrity, and use the
saved copy from then on. To save from the browser, use "Save Page" > "Web Page,
HTML Only", and use a filename of `TrustyHash.html`. To verify, read the
section on "Trust" below.
