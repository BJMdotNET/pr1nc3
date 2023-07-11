# PR1NC3

## Links to articles grouped by:

  * [publications](./publications/index.md)
  * [authors](./authors/index.md)
  * [dates](./dates/index.md)
  * [topics](./topics/index.md)

## Updates:

  * APNews updated its website in July 2023, and it means most of their older articles aren't available anymore.
     * And lots of those old articles were not archived by the Internet Archive's Wayback Machine.
     * This is unfortunate, since APNews had articles going back to the mid-1980s.
	 
## How to use:

  * Articles are grouped by author, publication, date and topic.
     * Which means an article written by Jem Aswad for Variety about the announcement of *Originals* in 2019 can be found at:
        * author: [Jem Aswad](https://bjmdotnet.github.io/pr1nc3/authors/jem-aswad/)
        * publication: [Variety](https://bjmdotnet.github.io/pr1nc3/publications/variety/)
        * topic: [Originals (album)](https://bjmdotnet.github.io/pr1nc3/topics/album/originals/)
        * date: [2019](https://bjmdotnet.github.io/pr1nc3/dates/2019/)
  * The "global search" at the top can be useful, but it only searches the contents of this site (and even this is limited).
     * Example: "Elisa" returns results, "Fiorillo" doesn't.
     * IMHO it is often far easier to use the "topics" grouping and then search in the left navigation for something.
	 
## Articles:

  * There are approximately 1937 links.
  * Some links might be duplicates, e.g. some AP News articles are linked through multiple links.
  * Some articles might be duplicated, usually because for instance an AP News article is republished elsewhere.
     * I try to avoid including such republished articles, but likely I've missed some instances.
  * Not all links are active anymore.
     * At the bottom of each entry is a link -- "(mirror)" -- to find the article in the Internet Archive's Wayback Machine.
        * There is no guarantee the article will be available there.
  * For some sites I have managed to automate the conversion from link -> html file -> database entry.
     * But even in those cases I need to check the result, which is time-consuming.
	 
## Authors:

  * Apologies to the authors who are not mentioned in an article's overview.
     * Linking authors to their articles is a separate, manual and time-consuming step.
	 
## Topics:

  * An article's list of topics might be incomplete and/or incorrect.
  * Topics might appear multiple times, for instance due to typographical differences.
  * Topics might be missing. 
     * I try to go through every article and look for topics not yet in the database, but this is time-consuming.
	 
## Publications:

  * Publications sometimes have "bad" names, basically their domain name.
     * Converting this into a proper name is a manual and time-consuming job.
	 
## Collaboration:

  * Unfortunately, you cannot contribute. I know there are tons of links 'missing', but it is what it is. 
     * Building a public back-end would take far too much effort and time, which I don't have.
	 
## Technology:

  * The (off-line) back-end was made in ASP.NET MVC.
  * Each article, publication etc. is stored as a JSON file.
     * This makes it easier to spot problems or errors etc.
  * A command-line application (written in .NET C#) converts these JSON files into Markdown files.
  * These Markdown files are converted into static HTML files with DocFX.
  * The UI is customized based on the CSS from the "DocFX Material" theme.
	 
## In general:

  * This site is barely in 'beta'. Keep your expectations low.

