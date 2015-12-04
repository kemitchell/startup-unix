# Startup Legal is Unix All Over Again

The legal structure of Silicon Valley-style startups is Unix all over again.

There are many flavors of startup legal docs. The major Silicon Valley law firms and some accelerators peddle house form sets. Just as you'd get [AIX](http://www.ibm.com/aix/) from IBM or [Solaris](http://oracle.com/solaris) from Sun, clients of, say, [Fenwick & West](http://fenwick.com) end up Fenwick-flavored startups, [Y Combinator](http://ycombinator.com) companies form as YC-flavored startups, and so on.

Lawyers who deal with startups recognize popular variants, but stick to one for their own work. The contours of that set—down to section numbers and defined terms—burn into memory. I'll have [`sudo apt-get install -y`](https://wiki.debian.org/Apt) burned in muscle memory 'til the day I die, just as the terms of the [Latham](http://lw.com)ite startup forms I trained on will always be fresh in mind. Sure, I can handle a [FreeBSD](http://freebsd.org) deployment or a [WSGR](http://wsgr.com)-founded company, but I'll spend a little time reading up and feeling my way around at the start.

Familiarity aside, startup flavors still aren't "all the same". They differ meaningfully in style, organization, and features. They [reflect the organizations that create them](https://en.wikipedia.org/wiki/Conway%27s_law), which differ in structure, structure, and habit. Updates appear with varying frequency from maintainers with different priorities, revised and released in different ways. Improvements crop up and spread, as with [DTrace](http://dtrace.org), so with [forum selection bylaws](http://www.delawarelitigation.com/2014/09/articles/chancery-court-updates/chancery-upholds-forum-selection-clause-outside-delaware/). Vulnerabilities, like the infamous [Benchmark gap](http://www.goodwinprocter.com/~/media/Files/Publications/Attorney%20Articles/2002/The_Benchmark_Case_and_the_Limits_of_Preferred_Stock_Protections.pdf), get plugged.

Yet the primary importance of compatibility unites the variations. The value of the banal, mission-critical legacy applications every startup has to run always overshadows any flavor-specific benefits, even when those benefits include lots less in legal and management time. If you've seen the word _whereas_ since starting your company, know you're running legacy legal. But you probably won't tank because you couldn't issue options as new hires expect, make the reps investors want, or sell preferred without going to jail.

The startup company as we know it is a solution to that system of constraints, a well-worn path through the thicket of law and Bay Area expectations. As far as I know, there has never been a definitive general statement of that solution—a [POSIX](https://en.wikipedia.org/wiki/POSIX), so to speak, of the Silicon Valley startup. But rare is the hacker who's read more than specific sections of POSIX in any event, and rare is the lawyer who's read the underlying case law and statutes. If you've gone that deep, chances are you hack operating systems or startup forms.

## The Law Firm Startup Distribution

To its credit, startup legal already had its [BSD](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution) moment. A number of very fine law firms release snapshots of their in-house forms on the Web. As far as I know, [Orrick](https://www.orrick.com/practices/emerging-companies/startup-forms/) blazed that trail. [Cooley](https://www.cooleygo.com/), [Gunderson](http://gunder.com), and [Perkins Coie](http://www.startuppercolator.com/) followed.

Anyone with the Internet can get the latest Orrick/Cooley/Gunderson/PK Startup Distribution. It's easier to read up on those forms and spot deviations from them. It's easier to train up as a startup lawyer. I'm not aware of any [particularly righteous beards](http://www.usenix.org.uk/content/unix_beards.html) at those firms, but those responsible deserve gratitude and respect.

While anyone can read those forms, they are practically read-only. Orrick begat Startup Library begat [Clerky](http://clerky.com) begat a bevy of startups. To land a patch upstream to the law firm, you go to work for the law firm and take it up to the committee or partner who tends the templates. Or you start out at the firm and leave to start a company, like the Clerky guys, and hock a fork of the canonical set. Whatever original changes you make, you have to rebase on every new release from the firm. Either that, do all your own work, or offer old forms.

## Open Future

The industry awaits a startup implementation that:

1. maintains compatibility with all the old "mission critical" legal applications

2. runs on modern process infrastructure, from document assembly to electronic signature, rather than entrenched law firms

3. releases in a transparent, predictable, and verifiable manner, for free, on the Internet

4. welcomes and acts on feedback, including "bug reports", from downstream users of all kinds

The Unix and startup stories diverge here. Startup legal doesn't require cleanroom rewriting to avoid a licensing issue. It doesn't need a port to a newer, cheaper, more universal platform. The community awaits an implementation that belongs to the community as a whole, rather than to any particular player, that is open, general, and adaptable enough for wide application.

Fundamentally, it's about process. A firm can standardize on documents that grow out of and mirror its own collaborative infrastructure and clientele. So can an accelerator. The tendency within such an environment is to optimize. The value of that optimization is real, but specializes the product to the organization. Underlying assumptions may not hold elsewhere, and may in fact work against inter-firm, inter-company adoption. In other words, against standardization.

The only precedent for that kind of standardization I'm aware of comes from industry groups. Finance has [an industry group that publishes standard forms](http://www.isda.org/). Insurance has [an industry group that publishes standard forms](http://iso.com). Even venture capitalists have [an industry group that publishes forms](http://nvca.org), though the law firms don't necessarily play along. 

There isn't a group representing the interests of startup companies. There ought to be. In its absence, what we have is competing, specialized implementations designed to lure new companies to one or another vendor of follow-on services, accountancy style. The answer is a state-of-the-art startup implementation developed with best-available tools for collaboration, promoted and refined by startups, for startups. When the construction industry got tired of the standard forms from the [architects' industry group](http://aia.org), they [started their own initiative](http://consensusdocs.org). Startups can do the same.

I'm on it. If you're interested, [drop me a line](mailto:kyle@kemitchell.com).
