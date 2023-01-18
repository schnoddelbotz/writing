# Writing & Language

> Everything You Always Wanted to Know About Writing 
> (but were afraid to ask)

[Woody Allen](https://www.youtube.com/watch?v=sj0YAuOiLBM)

"So kurz wie möglich, so ausführlich wie nötig."
As brief as possible - as detailed as needed.
That's one of the German quotes you may find here
as my attempt to support someone (or you) in writing
meaningful documents. Intent is to get you good grades
or whatever other positive response from your "sponsor".

A short, loose collection of hints on how to write.

## Introduction - From homeworks to academic writing

I put this document together for a friend who asked me
to help him write a 6-page article for school. I am
no educator but had to write a 100-page document myself
once and did not totally fail. So YMMV meaning your milage
may vary. Use my hints at your own risk.

I refuse ghostwriting but love to help, if I can.
Wish Dave the best.

If you're going through this adventure with me for the
first time, you'll need 6 sheets of paper. Yes.
I just decided 6 is good. I name them #S1 to #S6.
Maybe we can use 4-6 for airplanes in the end.

And you also need a pencil for you.
And one for your buddy, should you brainstorm together.
That's the point. Brainstorming as team is fine.
But YOU MUST WRITE THE FINAL TEXT. Imagine I, as German
would write for a Refugee in Switzerland. Nobody would
be helped. (I don't - just to let you see: Cheaters get caught).

## The task

It must be clear at this stage what kind (or "class") of document you are
supposed to produce. Here are some common german examples ..

| Name           | Where           | Contents                | Size |
|----------------|-----------------|-------------------------|------|
| Aufsatz        | Primary school  | Any freeform text work  | 1~5p |
| Erörterung     | Secondary school| Comments on some topic  | 1~5p | 
| Interpretation | Sec/Highschool  | Text understanding test | 1~5p |
| VA (Zurich)    | Lehre Lagerist etc | Free choice, choose well | 6p |
| Thesis Diplomarbeit Masterarbeit | Institutes of technology, Universities | Same as VA | ~100p |
| Dissertation   | University      | To gain Dr.             | Same as VA | 100+p|

Each document type has some STANDARD outline and contents the
reader WILL expect. Keep both in mind till the end to win.

## Getting started

If you haven't done SOME writing before, then this is the hardest part.
Don't worry, it's easy. Watch the A-Team. A good plan is what matters.
And you, verifying the plan DAILY to avoid surprises and meet the DEADLINE.
The deadline is an ugly word, in German: Abgabetermin - try: 
due date (Fälligkeitsdatum, literally).

Before typing down (or even typesetting) the document, we prepare the
tools needed to get the final document written easily.

REGARDLESS OF DOCUMENT TYPE we need at least these three things:

1. A Mindmap. A mindmap is used to explore your document topic using
   single words describing crucial / relevant corners you will mention,
   i.e. travel along while completing it. It's similar to a TagCloud
   found on the web - The tagcloud gives the words weight using size -
   That means words typeset in a larger font are (thought to be) more 
   relevant for the document itself and/or the reader (!).
   See my example below, which CENTERED around the MicroServices (IT) topic.

2. An Outline. The German Stichwort-Liste, the predecessor of the table of contents.
   Nothing more. Inhaltsverzeichnis draft. Overview of document structure and contents. 
   Brief. There should always be room for quick notes (#Brainstorming).

3. A schedule. Zeitplan. Time. Planning. 
   Two-fold. 
   FIRST, for each point of the outline, plan time required, compute total if you wish.
   That means break down the work into CLEARLY IDENTIFYABLE parts (so you can EASILY measure success),
   and stick them into your calendar. More later (Online services, git...)
   SECOND back to real life. You have a job? A life? Or a family? Or even both?
   Nice. They will all break your plan. Be realistic.
   PLAN to submit the paper 20% BEFORE deadline. Worst that can happen to you:
   You're done too early and have zero motivation to improve further. Then submit.

## Software for writing

Oh well. Many books have been written, this is one of them.
If you have a SIMPLE TEXT EDITOR you're feeling comfortable
with, maybe stick with it. The question here is, since decades:
Do you NEED WYSIWYG (What you see is what you get)? That term
was introduced when IT managed to display Adobe Type 1 or even
worse TrueType fonts (today ... replaced. Open.) on SCREEN in
REAL TIME while typing. That was a MILESTONE. Nobody really
needed. Anyhow. Both approaches exist today, and you can choose here:

- CONSOLE Text Editors: vi, vim, emacs, ...
- Graphical Text editors. I know it sounds weird. Thing is,
  back in the day, computer screens only displayed text.
  Then Xerox labs invented the GUI Graphical User Interface,
  things like the Mouse, later sold to Apple etc. X11.
  MIT. Well. You know Microsoft Windows? Before, there was MS-DOS.
  Also text mode (80x25 characters, default).
  TEXTMODE means: The OS tells the GRAPHICS CARD:
  Display TEXT: Hello.
  Done. Graphics mode (same monitor connected, yay!) means that
  the monitor has some resolution, e.g. SVGA 1024x768 pixels.
  Now the computer must compute the OUTLINE of some FONT,
  RENDER it (apply AntiAliasing etc.) and tell the Graphics card:
  Display this BITMAP at location X,Y on screen.
  And the bitmap is, per pixel on screen, a set of RED GREEN and BLUE 
  values, yielding ONE color dot per combination.
  Sorry. This does not belong in here. Must review.
- So graphical TEXT EDITORS: SublimeText, NotePad, NotePad++, TextMate, TextWrangler, BBEdit, nedit (Nirvana Editor, OLD), ...
- Graphical "document editors": Libre Office, Microsoft Word, ...

What I called document editors above are the WYSIWYG tools as of today.
Using them is NOT wrong, especially if you already KNOW them.

If you start from scratch, there are several reasons to go for pure text editors:
1. Revisioning. The graphical document editors all produce binary file formats, 
   which are plain shit to put under version control. Version control tools
   like GIT do not only provide a life long change history of your documents,
   but also serve as constant BACKUP. You CAN put binary files on git,
   but it simply makes no sense. Ask someone.
2. Focus. You are not paid for designing a document. Type setting is an art.
   VERY VERY few people study typography or even bother about it. Now, with
   type setting tools like LaTeX, YOU do not need to bother - cool, eh?
   The idea is that THE TEXT MATTERS FOR YOU. Do NOT WASTE TIME FORMATTING.
   That's the TASK of a typesetter.

Ja, that's it. So:

EITHER Text + Editor + Git + Latex OR some Graphical document editor, like MS-Word.

To give the Latex approach a quick try, visit OverLeaf - Latex environment in the browser.

Google "Latex download mac" to find MacTex for MacOS etc. I'll add links one day, maybe.

## From Outline to paragraphs, sections, chapters etc.

LaTeX offers various key elements to structure a document, DEPENDING on document type/class defined.

You should have some template document from your school,
requesting certain structure. So if using LaTeX for the task,
we should now go and figure out a matching document type
for our purpose.

```
```

See [texblog.org LaTeX documentclass options illustrated](https://texblog.org/2013/02/13/latex-documentclass-options-illustrated/)


# Legal

These tips come without warranty. See room for improvement?
This is OpenSource. Either file a pull request to help making this
document better or go on an ego trip, fork the repo and then
rewrite from scratch. Mentioning me is source would be nice
but I'm no dreamer.

As student, I'd stay away from ghostwriters. Maybe better ask
as friend to do brainstorming with you. Independent. New ideas.
That's allowed. Also keep in mind, most schools DO USE plagiarism
detection tools nowadays. The more retarded ones make a secret
out of the magic, transparent ones like Liverpool University
simply state: Submit via TurnItIn (which is a plagiarism checker).
The more universities participate, the bigger the fundus of
prior art gets. So you will be more and more limited in the
future. Good luck with that! Try reprhasing shit a thousand times.
And keep in mind those plagiarism checkers gain all your knowledge.

ETHICS is the core problem most governments have proven unable
so far to deal with - so don't start talking about IT. Not in
this decade. Go, grab your pencil now. PEACE.
