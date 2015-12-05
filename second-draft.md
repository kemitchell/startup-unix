# Startup Legal is Unix All Over Again

Startup legal structure is stuck in the Unix era, waiting for its "open" moment.

Every startup company has to run boring "business applications". Employees want stock options with standard tax benefits. Investors want a capital structure they can model. The guy in the tie at the bank won't give you a bank account without the right magic paper. Boring.

There are probably dozens of prepackaged legal form sets for starting and "booting up" a Silicon Valley style startup company. All of them are compatible with these and other basic, boring "business applications", with a little headroom for customization. The set you're running probably reflects who is selling you other kinds of products and services.

It's like that ancient program that accounting ran on the mainframe in the basement of your old job. AIX? Solaris? Who cares?

Vendors care. They probably sold accounting the mainframe, and the mainframe almost certainly runs "their" Unix. The army of consultants and technicians and training people in orbit around the vendor all know that Unix like the backs of their hands, in every gruesome detail and glorious selling point. It isn't so much that customers buy Such-and-Such Unix and try to think up things to run on it. They know what they need, compare a few to get it, and buy a solution as much for the follow-on companies, experts, and products as any intrinsic feature.

When you go to a startup-capable law firm and get yourself a corporation, you end up with the same basic Delaware corporation as everyone else. It's commodity legal hardware. But your Delaware corporation comes preloaded with the law firm's operating system, in the form of articles of incorporation, bylaws, basic agreements, and other documents. Those docs pick the ground rules and set the board for the business game that follows.

The lawyers at the firm know their "flavor" of startup legal down cold. The 409A valuation firms they refer know where to look for the parts they need. The form financing documents they have ready to go are built to run on them. There may even be some document preparation automation going on back office.

A good form set produces a legally compliant, business-ready corporation every time. That is the vast majority of its value. But that isn't to say all form sets are created equal. They reflect the institutions that make them.

If a firm has particular strength in, say, tax, its startup forms may develop more nuanced tax features. If the firm forms a lot of startups for foreign founders, its forms may better address immigration needs. If the firm has an active form revision committee, or a particularly dedicated "startup" partner, updates for changes in the law may land quicker.

Conversely, if a firm's lawyers still close documents on paper, its forms will be drafted to work with that process. If the partners like _wherein_s and _whereas_es, their forms will be littered with them. If the firm cannot or does not devote significant time to revision and rewriting, the forms will grow tattered with ad hoc edits, tacked-on provisos, and other tool marks. If a firm's clients are uniformly alike in some way---say they mostly come through a particular accelerator---the forms may become specialized to that kind of client.

## The Law Firm Standard Distribution

It's not quite as bad as that. Fortunately, startup legal has had its BSD moment.

A number of very fine law firms now release snapshots of at least part of their in-house forms on the Internet. As far as I know, Orrick blazed the trail, followed eventually by Cooley, Gunderson, Perkins Coie, and probably others.

Anyone can download the latest Orrick/Cooley/Gunderson/PK Distribution. It may not be easy to use, complete, or up-to-date, but the community is better off for the information. It's good education for budding businesspeople. It's invaluable for up-and-coming lawyers. And if you're familiar with the forms---many startup lawyers can "recognize" a law firm in the style of a company's founding docs---it can even save you time reviewing for meaningful changes. As a practicing attorney, I've no doubt the process of preparing the forms for publication benefited the forms and the firms' own clients, too.

And they've seeded some meaningful innovation. The Orrick set, for example, begat Clerky, which in turn begat a bevy of startups. Gunderson's release of its documents on Docracy was a boon. Legal technology startups and open-source projects love to demo with startup documents, because they're just so easy to get.

## Over the Wall

The Law Firm Standard Distributions are fundamentally read-only. Each firm has its own internal revision process, and those processes are time-intensive and expensive. Their output alone is tremendously valuable, but there's no clear channel for outside feedback or interaction, and no good incentive for it to begin with. To land a patch upstream to the law firm, you go to work for the law firm and take it up to the committee or partner who tends the templates.

Of course, you're free to "fork" your own variant of a publicly released set. What happens next? Either you revisit each of your changes every time the firm makes a new release, or you give up and go your own way. The proliferation of "house" form sets at law firms may come down to lawyers carrying their old "house" set with them as they changed law firms. Even within firms that have standard form sets, lawyers are known to keep private variants for their own work.

This kind of diversification doesn't effectively distribute meaningful improvements to startups. It doesn't rapidly distribute fixes to problems, either. It definitely doesn't reduce the burden on those who review startup legal documents, such as for investor due diligence. It basically functions to keep effort as little consolidated as possible.

## Open Process

The startup community doesn't need another set of free startup legal forms to download. It needs a process that focuses the disparate efforts of legal and business allies into a community owned, vendor neutral legal operating system for startups. We don't need another Unix, we need a Unix that runs on anyone's hardware that no one owns and anyone can improve. We need a 386BSD of startup legal.

Good news: there's precedent. In finance, the International Swaps and Derivatives Association (ISDA) publishes industry-standard derivatives documentation, and the Loan Trading and Syndication Association (LSTA) and Loan Market Association (LMA) publish debt syndication agreements. The Insurance Services Office (ISO) publishes standard form policies that enable meaningful cross-firm actuarial research and analysis. Even venture capitalists have the National Venture Capital Association (NVCA), which published standard venture capital financing documents. In the construction industry, associations of contractors and professionals formed ConsensusDocs as an alternative to the established contract forms published by the American Institute of Architects (AIA), which they thought unfairly privileged architects. These and countless other industry groups have come together to pool effort and encourage competition among service providers.

There isn't any group turning out startup legal documents in the interests of startup companies. There ought to be. In its absence, the community endures a dizzying array of competing, specialized legal sets that function to lure and lock new companies to one or another service provider. The answer is a state-of-the-art startup implementation developed with best-available tools for collaboration, promoted and refined by startup people, for startup people.

## Ironsides

We are happy to announce [_Ironsides_](https://github.com/ironsides/ironsides), a project for a truly open startup legal operating system. The project's goals:

1. Document corporations compatible with standard Silicon Valley style equity compensation, financing, and other "mission critical" transactions and relationships.
2. Favor no particular vendor, technology, or mode of legal practice for preparation or signature.
3. Release revisions in a transparent, predictable, and verifiable manner, for free, on the Internet.
4. Welcome and incorporate contributions from companies, attorneys, and other professionals, with startup companies' interests in mind.

The purpose of Ironsides is to learn from and serve the startup community, not to tell it what it should want. However, contributors have already done quite a bit of work preparing a strong starting point for the project. That existing work has sounded in a few strong themes:

1. Contributors have stressed that documents should be consistently organized and phrased, as much as possible, in plain language that non-lawyer readers can understand.
2. The documents are developed as plain text files, using open source software to create copies in other formats, as for Microsoft Word.
3. Contributors have taken to using GitHub, and especially its Issues and Pull Requests systems, for collaboration and planning.
4. All work thus far is made available under the terms of the [Creative Commons CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) public domain dedication.
5. Contributors have drafted processes for receiving proposals in the form of "redlines" (traditional legal markups) by e-mail and even postal mail, including anonymous proposals.

Ironsides' beginnings (and cool name) are the work of two individuals:

Jason Boehmig is founder and CEO of Ironclad, Inc., a legal document automation company that understands open-source software. Prior to founding Ironclad, Jason practiced business law in Silicon Valley and spearheaded the public release of the free Series Seed financing documents.

Kyle Mitchell is a business lawyer and open-source programmer. Prior to starting his own law practice, Kyle also practiced business law in Silicon Valley, and before that built web applications and instructional multimedia for a decade in Austin, Texas and Moscow, Russia.

Kyle maintains and contributes to _Ironsides_ with the generous support of Ironclad.
