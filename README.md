# ThesisTips

This document provides tips for writing a PhD thesis, collected during the process of writing my own thesis.
It is by no means exhaustive. If you have any tips you'd like to share, let me know!

## Resources

Here's a list of resources that may help you write your thesis. (To be extended.)

* [How to write a good PhD thesis and survive the viva - Stefan Rüger](http://people.kmi.open.ac.uk/stefan/thesis-writing.pdf)

## Tips

* **Start early** If you want to have a coherent story, you need to start early. This way, if there's a hole in your story somewhere, there's enough time to carry out additional experiments to fill the gap.

* **Get some examples** Try to get your hands on a couple of PhD theses, to see what they're like. Here are some questions you may want to ask yourself:
  - What do these have in common?
  - How do they differ?
  - What separates a good thesis from a bad one?
  - How are they structured, and which kind of structure suits my work best?

* **Don't be intimidated by the work of others** There are some brilliant PhD theses out there. But don't worry if you feel that your work isn't brilliant! It's better to see what an average PhD thesis looks like, and know that this is enough to get your PhD. There's an old joke that I read somewhere: Q. What do you call someone who just barely passed his PhD exam? A. Doctor. It's the end goal that matters here. Just start writing!

* **Write an outline of your thesis** Start by writing an outline of your thesis. Here are some questions you may want to ask yourself:
  - What is the story that you want to tell? 
  - How can you divide that into chapters? 
  - How are those chapters related to each other?
  - How does your work fit in those chapters?
  - What have you already done, and what do you still have to do?

* **Write a paper about your PhD work** I've found it super helpful to write a *PhD proposal* for the EACL student session. Other conferences may call this a *doctoral consortium paper*. This is just a paper detailing what you're working on for your PhD: background, motivation, preliminary results, plans for the future. If you do this about 2 years before you're supposed to finish, you'll have a decent idea of where you're going, and you can get feedback from experienced researchers that you can still incorporate in your plans. The paper can then serve as a basis for your thesis, so you won't have to start from scratch.

* **Start small** At the moment, you are one of the world experts in your research area. It's tempting to write a book about *everything you know*. But writing a book about everything will make your readers lose focus of what's important. This is a report about your accomplishments. Start with those. Then figure out what knowledge is presupposed by your work, and what knowledge people would need to contextualize your work. Stefan Rüdiger suggests taking a first year PhD student as a reference point; if they are be able to read your work, then you have succeeded. You can always expand the scope of your work if there is time. Narrowing down is a painful process.

* **Kill your darlings** You cannot put everything you've done in your thesis. Some results just aren't relevant for your thesis. Remember that you can always include a list of work published during your PhD as an appendix. Acknowledge your additional efforts there.

* **Keep a glossary** To remain consistent in your terminology, you may find it useful to write a small glossary with definitions as you're writing up your thesis. Forcing myself to keep this additional document made me realize how much jargon I'm using. It's a constant reminder that I should clarify terms that may be unfamiliar to the reader. Plus, at the end of this I'll have a sweet overview at the end of my thesis!

* **Always keep a pen and paper with you** This is a general life tip. But writing your thesis will occupy your mind for a good while, and you will have sudden realizations about where your thesis should be going. Especially when you are not anywhere near a computer. Write it down. Otherwise you *will* forget it.

* **BACKUP BACKUP BACKUP!** Have at least one backup. Regularly check that it's up-to-date. I write my thesis using LaTeX and use Git to commit my changes to Overleaf. Here's a small bash script that I use (the commit message doesn't matter for Overleaf). The `date` command reminds me when I last committed my work.

```bash
git add .
git commit -m "Updating my thesis"
git push
echo "This operation was carried out on:" ; date
```

* **More backups** You can also use Google Drive, Dropbox, another hard disk or flash drive. But back up your work! You do not want to know how many people have lost all of their PhD work due to a lack of backups.

* **Thesis templates** Ask around whether your university has a template for PhD theses in LaTeX. Many departments have one. Ours didnt, so I went with the *Memoir* document class in LaTeX. This is basically an enhanced version of the *book* document class. It's really well documented by Brian Wilson (as in: hundreds of pages of documentation), and there's also a stack overflow community around it. 

* **Bibliography management** I hear many great things about Zotero, but I mainly use BibDesk.

* **ACL anthology BibTeX** Did you know you can usually change the `.pdf` extension to `.bib` and get the BibTeX for papers in the Anthology? Very useful.

## Contributors

Emiel van Miltenburg

## Acknowledgments

Thanks to Desmond Elliott and Piek Vossen for supervising my PhD work. 
They deserve a lot of credit for giving me loads of useful advice along the way. 
Brian McMahan suggested I put these notes somewhere online. Here they are, Brian!
