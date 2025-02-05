---
title: Document shepherding
description: A short informal description of how shepherds help documents progress through the working group process.
published: true
date: 2024-11-07T14:39:14.601Z
tags: 
editor: markdown
dateCreated: 2022-05-09T14:28:44.149Z
---

# About document shepherding
A Document Shepherd makes sure an Internet-Draft (I-D) continues to progress appropriately through the IETF processes, keeping in mind the overall IETF goal of producing technically excellent documents. 

A document won't shepherd itself. Chairs are often occupied with other aspects of Working Group (WG) operations. An Area Director (AD) has to worry about many other documents. Authors sometimes vanish. WG Chairs therefore designate an individual as the shepherd for working group I-Ds.

A Document Shepherd takes responsibility for pushing a WG document along.  Firstly, to the point where the WG has consensus, and then—if that's acheived—through the Internet Engineering Steering Group (IESG) review, and finally through the RFC Editor (and IANA) processing. 

Per https://datatracker.ietf.org/doc/statement-iesg-iesg-statement-on-document-shepherds-20101011/, the IESG encourages the working group chair to select an active working group participant that has strong understanding of the document content, is familiar with the document history, and is familiar with the IETF standards process. The Document Shepherd of a working group document should not be an author or editor of the document.

Some working groups also avoid appointing Shepherds who are affiliated with an author or editor of the document. Affiliation should be evaluated on a case-by-case basis, e.g., individuals in different divisions of a large company  may be considered to have sufficient independence to permit a  Shepherd and a author from the same company on the same document.
    
More detail about the document shepherding process can be found in:
* [RFC 4858](https://www.rfc-editor.org/rfc/rfc4858.html)
* [A description of the document lifecyle](/documents/lifecycle)
* [IESG Statement on Document Shepherds](https://datatracker.ietf.org/doc/statement-iesg-iesg-statement-on-document-shepherds-20101011/)

## Document shepherd writeup

One of the key things a Document Shepherd does is to write up the history of a document's path through the WG process. The purpose of the shepherd writeup is to make sure that the document has been properly reviewed, information which the IESG uses in its IESG Evaluation of a document. The IESG has provided a [writeup template for individual submissions](https://datatracker.ietf.org/doc/shepherdwriteup-template/individual) and a [writeup template for working group submissions](https://datatracker.ietf.org/doc/shepherdwriteup-template/workinggroup) as a guides.

The document shepherd writeup is not subject to working group consensus. Quite the opposite, it's the place for the shepherd to communicate with the ADs, and SHOULD include information that the Document Shepherd thinks is important, even—or especially—if the WG isn't in agreement.

## Intended status

The writeup should be explicit about which document the writeup is about  and its target status (e.g. [Informational](https://datatracker.ietf.org/doc/html/rfc2026#section-4.2.2), [Proposed Standard](https://datatracker.ietf.org/doc/html/rfc6410#section-2.1)). Working Group charters or milestones are sometimes unclear about the intended status of a document. And, the WG may decide to change the intended status based on consensus. (This should be discussed with the WG's AD.) Therefore, to avoid problems, and to make it clear in the WG process what is happening, it's strongly recommended that the WG chairs do the following:

* Check that WG documents have the right intended status in the I-D header. This is occasionally in error.
* When performing a WG Last Call, write explicitly in the WG Last Call message to the mailing group email list what the intended status is.
* When reviewing the shepherd writeup, be sure it is explicit about which document the writeup is about, including that the target status is.