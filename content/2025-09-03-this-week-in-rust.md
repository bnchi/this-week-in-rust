Title: This Week in Rust 615
Number: 615
Date: 2025-09-03
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at
[@thisweekinrust.bsky.social](https://bsky.app/profile/thisweekinrust.bsky.social) on Bluesky or
[@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or
[send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust) and archives can be viewed at [this-week-in-rust.org](https://this-week-in-rust.org/).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

Want TWIR in your inbox? [Subscribe here](https://this-week-in-rust.us11.list-manage.com/subscribe?u=fd84c1c757e02889a9b08d289&id=0ed8b72485).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the linked Page](https://example.com/my_article)

If you add a link to a non-text content please prefix it with `[video]` or `[audio]`:

* [video] [Title of the linked video](https://example.com/my_video_article)
* [audio] [Title of the linked audio file](https://example.com/my_podcast)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Foundation
* [Welcoming the Rust Innovation Lab | Rust Blog](https://blog.rust-lang.org/2025/09/03/welcoming-the-rust-innovation-lab/)

### Newsletters
* [The Embedded Rustacean Issue #53](https://www.theembeddedrustacean.com/p/the-embedded-rustacean-issue-53)
* [Rust Trends Issue #69: Rust's Enterprise Breakthrough Year](https://rust-trends.com/newsletter/rust-enterprise-breakthrough-2025)

### Project/Tooling Updates
* [The road to SeaQuery 1.0](https://www.sea-ql.org/blog/2025-08-30-sea-query-1.0/)
* [rkik v1.0.0 - stateless NTPv4/v6 inspection CLI in Rust](https://github.com/aguacero7/rkik)
* [Introducing cargo safe-publish](https://blog.weiznich.de/blog/cargo-safe-publish/)
* [Tracking trust with Rust in the kernel](https://lwn.net/SubscriberLink/1034603/5dcfecdd5e3af0c2/)
* [Slint 1.13 Released with Live-Preview for Rust and C++](https://slint.dev/blog/slint-1.13-released)

### Observations/Thoughts
* [Rust Algorithm Bites – Binary Tree Level Order Traversal](https://d34dl0ck.me/rust-algorithm-bites-binary-tree-level-order-traversal/index.html)
* [Adding derive(From) to Rust](https://kobzol.github.io/rust/2025/09/02/adding-derive-from-to-rust.html)
* [Why I Built TLQ (Tiny Little Queue)](https://nebjak.dev/blog/why-i-built-tlq-tiny-little-queue/)
* [Combining struct literal syntax with read-only field access](https://kobzol.github.io/rust/2025/09/01/combining-struct-literal-syntax-with-read-only-field-access.html)
* [Be Careful Zero-Copying Strings with `serde`](https://bd103.github.io/blog/2025-09-01-zero-copying-strings-serde)
* [Elephants for breakfast: testing untestable functions, one bite at a time](https://bitfieldconsulting.com/posts/elephants-for-breakfast) 
* [Demangling the Details: Symbol Resolution in Rusty Trap](https://system.joekain.com/2025/08/31/demangling-the-details-symbol-resolution.html)
* [video] [Rust 1.89.0](https://youtu.be/C5RHSqYIR7w)

### Rust Walkthroughs
* [Let's write a macro in Rust - Part 2](https://hackeryarn.com/post/rust-macros-2/)
* [How to set up Rust logging in AWS Lambda for AWS CloudWatch](https://forgestream.idverse.com/blog/20250902-cloudwatch-rust-logging/)
* [Building a Todo App in GPUI](https://blog.0xshadow.dev/posts/learning-gpui/gpui-todo-app/)

### Research
* [Sharing a mutable reference with Python](https://blog.lilyf.org/posts/python-mutable-reference/)
* [Faster Rust builds on Mac](https://nnethercote.github.io/2025/09/04/faster-rust-builds-on-mac.html)
* [Rust Performance Tricks](https://davidlattimore.github.io/posts/2025/09/02/rustforge-wild-performance-tricks.html)
* [video] [Embedded Rust Workshop](https://www.youtube.com/live/PZZfVAaYTP8?si=2nfis0-IrN9aMkti)
* [video] [RustCurious 1: Why Rust is Safe: A novel introduction to ownership and borrowing](https://www.youtube.com/watch?v=lVWiHIVXG2c)

### Miscellaneous
* [Elements of Rust: A complete map of the Rust type system](https://rustcurious.com/elements/)
* [filtra.io interview with `tonari` team | Opening Portals With Rust](https://filtra.io/rust/interviews/tonari-aug-25)
* [audio] [Hyper with Sean McArthur](https://www.youtube.com/watch?v=aw9lvs3PhWQ)
* [video] [Berkeley Seminar | The quest for performance](https://youtu.be/k_-6KI3m31M?si=JDZTHRDTs-unM34A)

## Crate of the Week

This week's crate is [aehobak](https://crates.io/crates/aehobak), a transcoder for bsdiff binary patches.

Thanks to [David Michael Barr](https://users.rust-lang.org/t/crate-of-the-week/2704/1465) for the suggestion!

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Calls for Testing
An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.

If you are a feature implementer and would like your RFC to appear in this list, add a
`call-for-testing` label to your RFC along with a comment providing testing instructions and/or
guidance on which aspect(s) of the feature need testing.

* *No calls for testing were issued this week by
  [Rust](https://github.com/rust-lang/rust/labels/call-for-testing),
  [Rust language RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing),
  [Cargo](https://github.com/rust-lang/cargo/labels/call-for-testing) or
  [Rustup](https://github.com/rust-lang/rustup/labels/call-for-testing).*

[Let us know](https://github.com/rust-lang/this-week-in-rust/issues) if you would like your feature to be tracked as a part of this list.

### [RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing)

### [Rust](https://github.com/rust-lang/rust/labels/call-for-testing)

### [Rustup](https://github.com/rust-lang/rustup/labels/call-for-testing)

If you are a feature implementer and would like your RFC to appear on the above list, add the new `call-for-testing`
label to your RFC along with a comment providing testing instructions and/or guidance on which aspect(s) of the feature
need testing.

## Call for Participation; projects and speakers

### CFP - Projects

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

*No Calls for participation were submitted this week.*

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines] or through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

[guidelines]:https://github.com/rust-lang/this-week-in-rust?tab=readme-ov-file#call-for-participation-guidelines

### CFP - Events

Are you a new or experienced speaker looking for a place to share something cool? This section highlights events that are being planned and are accepting submissions to join their event as a speaker.

*No Calls for papers or presentations were submitted this week.*

If you are an event organizer hoping to expand the reach of your event, please submit a link to the website through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

## Updates from the Rust Project

383 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2025-08-26..2025-09-02

#### Compiler
* [detect missing `if let` or `let-else`](https://github.com/rust-lang/rust/pull/145582)
* [fix `#[loop_match]` on diverging loop](https://github.com/rust-lang/rust/pull/144783)

#### Library
* [add `Bound::copied`](https://github.com/rust-lang/rust/pull/145968)
* [add `Duration::from_nanos_u128`](https://github.com/rust-lang/rust/pull/145969)
* [add `Option::reduce`](https://github.com/rust-lang/rust/pull/144274)
* [implement Sum and Product for `Saturating(u*)`](https://github.com/rust-lang/rust/pull/144275)
* [implementation: `#[feature(nonpoison_condvar)]`](https://github.com/rust-lang/rust/pull/144651)
* [optimize `.ilog({2,10})` to `.ilog{2,10}()`](https://github.com/rust-lang/rust/pull/145776)
* [str: stabilize `round_char_boundary` feature](https://github.com/rust-lang/rust/pull/145756)

#### Cargo
* [`fix(cli)`: Show the bad manifest path](https://github.com/rust-lang/cargo/pull/15896)
* [add more context to publish-failed error message](https://github.com/rust-lang/cargo/pull/15879)
* [feat: don't stop at first error when emitting lints and warnings](https://github.com/rust-lang/cargo/pull/15889)

#### Clippy
* [`map_identity`: suggest making the variable mutable when necessary](https://github.com/rust-lang/rust-clippy/pull/15268)
* [`unit_cmp`: don't lint on explicitly written unit expr](https://github.com/rust-lang/rust-clippy/pull/15562)
* [allow `--print=crate-root-lint-levels`](https://github.com/rust-lang/rust-clippy/pull/15567)
* [`assertions_on_result_states` avoid changing return type in more cases](https://github.com/rust-lang/rust-clippy/pull/15591)
* [`collapsible_match` suggest ref/derefs when needed](https://github.com/rust-lang/rust-clippy/pull/14221)
* [enable `clippy::panic` in const contexts](https://github.com/rust-lang/rust-clippy/pull/15565)
* [fix false positive of `needless_range_loop` when meeting multidimensional array](https://github.com/rust-lang/rust-clippy/pull/15486)
* [fix `alloc_instead_of_core` false positive when `alloc` is an alias](https://github.com/rust-lang/rust-clippy/pull/15581)
* [fix `needless_for_each` suggesting wrongly with explicit closure input types](https://github.com/rust-lang/rust-clippy/pull/15595)
* [fix `print_literal` suggesting wrongly for inline literal following a numbered arg](https://github.com/rust-lang/rust-clippy/pull/15583)
* [fix `redundant_closure` suggests wrongly with deref overload](https://github.com/rust-lang/rust-clippy/pull/15077)
* [supress `excessive_precision` when constants are overly precise](https://github.com/rust-lang/rust-clippy/pull/15193)

#### Rust-Analyzer
* [add progress bars to more places in analysis-stats](https://github.com/rust-lang/rust-analyzer/pull/20560)
* [attach the db in one more place in highlighting](https://github.com/rust-lang/rust-analyzer/pull/20553)
* [avoid `--target` option being given twice to `rustc` when invoked through `cargo rustc` while fetching target data layout](https://github.com/rust-lang/rust-analyzer/pull/20579)
* [deduplicate methods in completion by function ID and not by name](https://github.com/rust-lang/rust-analyzer/pull/20587)
* [in `highlight_related,` when on an unsafe block, don't highlight unsafe operations of other unsafe blocks](https://github.com/rust-lang/rust-analyzer/pull/20547)
* [when mapping next-solver's `dyn` type, add `Self` (aka. bound var ^1.0) to auto traits' substitutions](https://github.com/rust-lang/rust-analyzer/pull/20563)
* [cache trait solving across queries in the same revision](https://github.com/rust-lang/rust-analyzer/pull/20527)

### Rust Compiler Performance Triage

A relatively quiet week. [#144841](https://github.com/rust-lang/rust/pull/144841) added an
optimization for incremental builds that provided a very nice win for the `nalgebra` crate. [#143290](https://github.com/rust-lang/rust/pull/143290) should help avoid instantiating async functions repeatedly in
downstream crates.

Triage done by **@kobzol**..-
Revision range: [ee361e8f..75ee9ffd](https://perf.rust-lang.org/?start=ee361e8fca1c30e13e7a31cc82b64c045339d3a8&end=75ee9ffd5ed3649c0a09493057adaa8feebb2035&absolute=false&stat=instructions%3Au)

**Summary**:

| (instructions:u)                   | mean  | range          | count |
|:----------------------------------:|:-----:|:--------------:|:-----:|
| Regressions ❌ <br /> (primary)    | 0.3%  | [0.2%, 0.4%]   | 7     |
| Regressions ❌ <br /> (secondary)  | 2.0%  | [0.1%, 13.6%]  | 30    |
| Improvements ✅ <br /> (primary)   | -1.9% | [-7.0%, -0.3%] | 17    |
| Improvements ✅ <br /> (secondary) | -0.7% | [-1.7%, -0.1%] | 23    |
| All ❌✅ (primary)                 | -1.2% | [-7.0%, 0.4%]  | 24    |

1 Regression, 3 Improvements, 6 Mixed; 5 of them in rollups
45 artifact comparisons made in total

[Full report here](https://github.com/rust-lang/rustc-perf/blob/27c08698d3d9cb15081459cf61385d52958e14ac/triage/2025/2025-09-02.md).

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* *No RFCs were approved this week.*

### Final Comment Period

Every week, [the team](https://www.rust-lang.org/team.html) announces the 'final comment period' for RFCs and key PRs
which are reaching a decision. Express your opinions now.

#### Tracking Issues & PRs
##### [Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [don't apply temporary lifetime extension rules to non-extended `super let`](https://github.com/rust-lang/rust/pull/145838)
* [disposition: not specified] [Stabilize `new_zeroed_alloc`](https://github.com/rust-lang/rust/pull/144091)
* [Do not materialise X in [X; 0] when X is unsizing a const](https://github.com/rust-lang/rust/pull/145277)
* [Reject invalid literal suffixes in tuple indexing, tuple struct indexing, and struct field name position](https://github.com/rust-lang/rust/pull/145463)
* [Stabilize `std::panic::Location::file_as_c_str`](https://github.com/rust-lang/rust/pull/145664)
* [Fix backtraces with `-C panic=abort` on linux; emit unwind tables by default](https://github.com/rust-lang/rust/pull/143613)
* [Specialize Iterator::eq{_by} for TrustedLen iterators](https://github.com/rust-lang/rust/pull/137122)

*No Items entered Final Comment Period this week for
[Rust RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period),
[Cargo](https://github.com/rust-lang/cargo/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc),
[Language Team](https://github.com/rust-lang/lang-team/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc+),
[Language Reference](https://github.com/rust-lang/reference/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc) or
[Unsafe Code Guidelines](https://github.com/rust-lang/unsafe-code-guidelines/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc).*

Let us know if you would like your PRs, Tracking Issues or RFCs to be tracked as a part of this list.

#### [New and Updated RFCs](https://github.com/rust-lang/rfcs/pulls)
* *No New or Updated RFCs were created this week.*

## Upcoming Events

Rusty Events between 2025-09-03 - 2025-10-01 🦀

### Virtual
* 2025-09-02 - 2025-09-05 | Hybrid (Seattle, WA, US) | [RustConf](https://rustconf.com/)
    * [**RustConf 2025**](https://rustconf.com/)
* 2025-09-03 | Virtual (Cardiff, UK) | [Rust and C++ Cardiff](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/events/)
    * [**Hybrid event with Rust Dortmund!**](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/events/310730387)
* 2025-09-06 | Virtual (Kampala, UG) | [Rust Circle Meetup](https://www.eventbrite.com/o/rust-circle-kampala-65249289033)
    * [**Rust Circle Meetup**](https://www.eventbrite.com/e/rust-circle-meetup-tickets-628763848597)
* 2025-09-07 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Rust Readers Discord Discussion: Rust Atomics and Locks**](https://www.meetup.com/dallasrust/events/310002479)
* 2025-09-09 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Second Tuesday**](https://www.meetup.com/dallasrust/events/305361533)
* 2025-09-09 | Virtual (London, UK) | [Women in Rust](https://www.meetup.com/women-in-rust)
    * [**From First Lines to First Clients: Carol Nichols on Building a Career in Rust**](https://www.meetup.com/women-in-rust/events/310102318)
* 2025-09-11 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/305646019)
* 2025-09-11 | Virtual (San Diego, CA, US) | [San Diego Rust](https://www.meetup.com/san-diego-rust/events/)
    * [**San Diego Rust September 2025 Online Meetup**](https://www.meetup.com/san-diego-rust/events/310326567)
* 2025-09-14 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Rust Readers Discord Discussion: Rust Atomics and Locks**](https://www.meetup.com/dallasrust/events/310002480)
* 2025-09-15 | Virtual (Charlottesville, VA, US) | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup/events/)
    * [**Setup Tock OS in a virtual environment (online) - prep for Sep 17**](https://www.meetup.com/charlottesville-rust-meetup/events/310706165/)
* 2025-09-16 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc/events/)
    * [**Mid-month Rustful**](https://www.meetup.com/rustdc/events/306757758)
* 2025-09-17 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/events/)
    * [**Rust Study/Hack/Hang-out**](https://www.meetup.com/vancouver-rust/events/307731033)
* 2025-09-18 | Virtual (Nürnberg, DE) | [Rust Nuremberg](https://www.meetup.com/rust-noris/events/)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/305646039/)
* 2025-09-23 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Fourth Tuesday**](https://www.meetup.com/dallasrust/events/305361443)
* 2025-09-25 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/306046637)
* 2025-10-01 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs/events/)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/wqzhftyhcnbcb)

### Africa
* 2025-09-09 | Johannesburg, ZA | [Johannesburg Rust Meetup](https://www.meetup.com/johannesburg-rust-meetup/events/)
    * [**Rust by Example - Primitives and Custom Types**](https://www.meetup.com/johannesburg-rust-meetup/events/310714835)

### Asia
* 2025-09-13 | Hangzhou, CN | [WebAssembly and Rust Meetup (Wasm Empowering AI)](https://www.meetup.com/wasm-rust-meetup/events/)
    * [**GOSIM AI Hangzhou 2025 (CFP is still open)**](https://www.meetup.com/wasm-rust-meetup/events/309987624)
* 2025-09-13 - 2025-09-14 | Hangzhou, CN | [GOSIM](https://hangzhou2025.gosim.org/schedule/)
    * [**GOSIM Hangzhou 2025**](https://dev.events/conferences/rust-global-china-and-rust-china-conf-2025-dscrf0e1)
* 2025-09-17 | Tel Aviv-yafo, IL | [Rust 🦀 TLV](https://www.meetup.com/rust-tlv/events/)
    * [**In person Rust September 2025 at Varonis in Herzeliya**](https://www.meetup.com/rust-tlv/events/310708628)

### Europe
* 2025-09-03 | Dortmund, DE | [Rust Dortmund](https://www.meetup.com/rust-dortmund/events/)
    * [**Rust for Safety-Critical Software-Development and other high potential Use Cases**](https://www.meetup.com/rust-dortmund/events/308517658)
* 2025-09-03 | Edinburgh, UK | [Rust and Friends](https://www.meetup.com/rust-edi/events/)
    * [**Want a Squeezable / Modern / Helpful / Wide Language? Choose Four**](https://www.meetup.com/rust-and-friends/events/310536614)
* 2025-09-03 | Frankfurt, DE | [Rust Rhein-Main](https://www.meetup.com/rust-rhein-main)
    * [**From bugs to parallelism to future-proofing: What makes Rust different**](https://www.meetup.com/rust-rhein-main/events/310322369)
* 2025-09-03 | Oxford, UK | [Oxford ACCU/Rust Meetup.](https://www.meetup.com/oxford-rust-meetup-group)
    * [**September fun**](https://www.meetup.com/oxford-rust-meetup-group/events/310579981)
* 2025-09-04 | Berlin, DE | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Berlin on location 🏳️‍🌈 - Edition 006**](https://www.meetup.com/rust-berlin/events/310800817)
* 2025-09-04 | Gdansk, PL | [Rust Gdansk](https://www.meetup.com/rust-gdansk/events/)
    * [**Rust Gdansk Meetup #10**](https://www.meetup.com/rust-gdansk/events/310610993)
* 2025-09-10 | Reading, UK | [Reading Rust Workshop](https://www.meetup.com/reading-rust-workshop)
    * [**Reading Rust Meetup**](https://www.meetup.com/reading-rust-workshop/events/308944038)
* 2025-09-11 | Bern, CH | [Rust Bern](https://www.meetup.com/rust-bern/events/)
    * [**2025 Rust Talks Bern #4 @Zühlke**](https://www.meetup.com/rust-bern/events/309903540)
* 2025-09-16 - 2025-09-18 | Berlin, DE | [Oxidize Conference] (https://oxidizeconf.com/)
    * [**Oxidize Conference**](https://oxidizeconf.com/)
* 2025-09-16 | Leipzig, DE | [Rust - Modern Systems Programming in Leipzig](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/)
    * [**Topic TBD**](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/308592250)
* 2025-09-17 | Girona, ES | [Rust Girona](https://lu.ma/rust-girona) | [Silicon Girona](https://silicongirona.club)
    * [**Rust Girona Hack & Learn 09 2025**](https://lu.ma/ql3u6q5u)
* 2025-09-18 | Aarhus, DK | [Rust Aarhus](https://www.meetup.com/rust-aarhus/events/)
    * [**Talk Night at Mjølner Informatics**](https://www.meetup.com/rust-aarhus/events/310562343)
* 2025-09-24 | München, DE | [Rust Munich](https://www.meetup.com/rust-munich/events/)
    * [**Rust Munich 2025 / 3 - hybrid**](https://www.meetup.com/rust-munich/events/307105978)
* 2025-10-01 | Olomouc, CZ | [Rust Moravia](https://www.meetup.com/rust-moravia/events/)
    * [**4. Rust Moravia Meetup (In the capital!)**](https://www.meetup.com/rust-moravia/events/310743282)

### North America
* 2025-09-02 - 2025-09-05 | Hybrid (Seattle, WA, US) | [RustConf](https://rustconf.com/)
    * [**RustConf 2025**](https://rustconf.com/)
* 2025-09-03 | Phoenix, AZ, US | [Desert Rust](https://www.meetup.com/desert-rustaceans)
    * [**RustConf 2025 Watch Party (Day 1)**](https://www.meetup.com/desert-rustaceans/events/310345446)
* 2025-09-04 | Montréal, QC, CA | [Rust Montréal](https://www.meetup.com/rust-montreal/events/)
    * [**September Monthly Social**](https://www.meetup.com/rust-montreal/events/310802460)
* 2025-09-04 | Mountain View, CA, US | [Hacker Dojo](https://www.meetup.com/hackerdojo/events/)
    * [**RUST MEETUP at HACKER DOJO**](https://www.meetup.com/hackerdojo/events/310547154)
* 2025-09-04 | Phoenix, AZ, US | [Desert Rust](https://www.meetup.com/desert-rustaceans)
    * [**RustConf 2025 Watch Party (Day 2)**](https://www.meetup.com/desert-rustaceans/events/310345459)
* 2025-09-04 | Saint Louis, MO, US | [STL Rust](https://www.meetup.com/stl-rust)
    * [**emulation of retro systems (NES, Gameboy) in Rust**](https://www.meetup.com/stl-rust/events/310116988)
* 2025-09-06 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust)
    * [**Beacon Hill Rust Lunch, Sep 6**](https://www.meetup.com/bostonrust/events/310106310)
* 2025-09-09 | New York, NY, US | [Rust NYC](https://www.meetup.com/rust-nyc/events/)
    * [**Rust NYC: Geometry in Rust at Motif + Rust on RISC‑V/ESP32**](https://www.meetup.com/rust-nyc/events/310795569)
* 2025-09-10 | Phoenix, AZ, US | [Desert Rust](https://www.meetup.com/desert-rustaceans/events/)
    * [**Rust <> JS**](https://www.meetup.com/desert-rustaceans/events/310669989)
* 2025-09-11 | Lehi, UT, US | [Utah Rust](https://www.meetup.com/utah-rust/events/)
    * [**Mazes and Graphs in Rust**](https://www.meetup.com/utah-rust/events/310674937)
* 2025-09-11 | México City, MX | [Rust MX](https://www.meetup.com/rust-mx/events/)
    * [**Polars para análisis y manipulación de datos**](https://www.meetup.com/rust-mx/events/310408223)
* 2025-09-14 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Davis Square Rust Lunch, Sep 14**](https://www.meetup.com/bostonrust/events/310106317)
* 2025-09-16 | San Francisco, CA, US | [San Francisco Rust Study Group](https://www.meetup.com/san-francisco-rust-study-group/events/)
    * [**Rust Hacking in Person**](https://www.meetup.com/san-francisco-rust-study-group/events/308284339)
* 2025-09-16 | San Francisco, CA, US | [Vara Network](https://lu.ma/events-by-vara-gear)
    * [**Rust Workshop by Vara Network**](https://luma.com/1bii0kv7)
* 2025-09-17 | Charlottesville, VA, US | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup/events/)
    * [**Tick, Tock, talk—find out how Rust secures embedded devices**](https://www.meetup.com/charlottesville-rust-meetup/events/310603587) | [**Online setup event Sep 15**](https://www.meetup.com/charlottesville-rust-meetup/events/310706165/)
* 2025-09-18 | Nashville, TN, US | [Music City Rust Developers](https://www.meetup.com/music-city-rust-developers/events/)
    * [**Rust on Bare Metal Series 3 : Place Holder**](https://www.meetup.com/music-city-rust-developers/events/304333261)
* 2025-09-18 | Seattle, WA, US | [Seattle Rust User Group](https://www.meetup.com/join-srug/events/)
    * [**September, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/308677324)
* 2025-09-24 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx/events/)
    * [**Rust Lunch - Fareground**](https://www.meetup.com/rust-atx/events/310287849)
* 2025-09-25 | Atlanta, GA, US | [Rust Atlanta](https://www.meetup.com/rust-atl/events/)
    * [**Rust-Atl At Manuels Tavern**](https://www.meetup.com/rust-atl/events/308675983)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## Jobs
<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

Please see the latest [Who's Hiring thread on r/rust](https://www.reddit.com/r/rust/comments/1mnpd9p/official_rrust_whos_hiring_thread_for_jobseekers/)

# Quote of the Week

> Bugs like this are the worst! It's almost impossible to catch them in development, because there is never enough load on the system to force the scheduler to move the execution to another thread. So, you end up with one of these "impossible to reproduce, fails sometimes, but never for you" bugs.
>
> It's mind-blowingly cool that the Rust compiler can detect something like this. And that seemingly unrelated parts of the language, like mutexes, lifetimes and async operations form such a coherent system.

– [Bernard Kolobara on their blog](https://lubeno.dev/blog/rusts-productivity-curve)

Thanks to [llogiq](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1711) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [U007D](https://github.com/U007D), [joelmarcey](https://github.com/joelmarcey), [mariannegoldin](https://github.com/mariannegoldin), [bennyvasquez](https://github.com/bennyvasquez), [bdillo](https://github.com/bdillo)*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](https://www.reddit.com/r/rust/comments/1n8du9a/this_week_in_rust_615/)</small>
