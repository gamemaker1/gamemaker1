# Vedant Kulkarni

## About Me

I am an undergraduate computer science student at
[IIIT Hyderabad](https://www.iiit.ac.in). I have contributed 400+ issues/PRs
across 30+ repositories over the past seven years - starting with my first PR
for Google Code-In in 2018, to working with MIT Media Lab’s Large Population
Models (LPM) team on their [AgentTorch](https://lpm.media.mit.edu/docs) project
for differentiable agent based learning in April 2024, and most recently with
Google Deepmind to [extend and benchmark function calling in the Gemma 3 family
of models](https://gamemaker1.github.io/projects/offline-function-calling)
since May 2025.

I’m the co-maintainer for the popular node.js libraries
[express-rate-limit](#express-rate-limit) and
[express-slow-down](#express-slow-down) used to shield servers from DDOS
attacks, contributor to [vercel/serve](#vercelserve),
[Refined Github](#refined-github), [FPM](#jordansisselfpm),
[Beckn](https://github.com/beckn),
[Sunbird Registries and Credentials](#sunbird-rc), and have created projects
such as [Dabbu](#dabbu-knowledge-platform) (a knowledge platform),
[office-text-extractor](#office-text-extractor), as well as [yeet](#yeet) (a
package manager for Arch Linux), amongst others. I participated in the national
ONDC Grand Hackathon in 2022 and my team won a special mention award. I was also
invited to give a talk titled 'A 12 Grader's Journey to Opensource Contribution
via Sunbird and Beckn' at the
[Sunbird DPG Tech Fusion Conference](https://lu.ma/kinhufit) in 2024.

## Projects That I Maintain

#### [express-rate-limit](https://github.com/express-rate-limit/express-rate-limit)

> _2.7k stars, 7.6M dl/month_
> ([list of authored pull requests](https://github.com/express-rate-limit/express-rate-limit/pulls?q=author%3Agamemaker1))

Rewrote the library in Typescript, created the modern store interface and
continue to maintain it alongside [@nfriedly](https://github.com/nfriedly), the
original author. Help in maintaining 7 out of the 8
[stores written for the library](https://express-rate-limit.mintlify.app/reference/stores),
and
[helped rewrite](https://github.com/express-rate-limit/express-rate-limit/pull/378)
the default memory store to make it more memory-efficient.

---

#### [express-slow-down](https://github.com/express-rate-limit/express-rate-limit)

> _230+ stars, 95k dl/month_

Helped with the rewrite in Typescript, and achieving feature parity with
express-rate-limit. I continue to maintain it alongside
[@nfriedly](https://github.com/nfriedly), the original author.

---

#### [agent-torch](https://github.com/AgentTorch/AgentTorch)

> part of the Large Population Models project by MIT Media Lab

Created a custom model using the framework to simulate movement of predator and
prey on a map of Central Park, NY. Also added a feature that allows for easier
declaration of substeps using decorators.

Currently working on improving the Python API, creating interactive simulations
for various use cases such as solar panel adoption, zoning policy, as well as
integrating it with Beckn.

## Projects That I Have Contributed To

#### [vercel/serve](https://github.com/vercel/serve)

> _9.1k stars, 6.6M dl/month_
> ([5 merged pull requests](https://github.com/vercel/serve/pulls?q=author%3Agamemaker1))

Refactored the library, added tests, and transitioned to ESM + Typescript.

---

#### [refined-github](https://github.com/refined-github/refined-github)

> _22.8k stars, 80k+ users_
> ([14 merged pull requests](https://github.com/refined-github/refined-github/pulls?q=author%3Agamemaker1))

Contributed to 8 popular features, including useful-not-found-page,
restore-file, quick-comment-edit, linkify-code and forked-to.

---

#### [jordansissel/fpm](https://github.com/jordansissel/fpm)

> _11k stars_
> ([1 merged pull request](https://github.com/jordansissel/fpm/pulls?q=author%3Agamemaker1))

Restructured the documentation, rewrote parts of the installation page, added a
getting started page, tutorials and examples, as well as a CLI flags reference
page.

---

#### [timocov/dts-bundle-generator](https://github.com/timocov/dts-bundle-generator)

> _660+ stars, 187k dl/month_
> ([1 merged pull request](https://github.com/timocov/dts-bundle-generator/pulls?q=author%3Agamemaker1))

Fixed a bug where the library does not export-default an expression when
re-exporting the default export from another file.

---

#### [flutter/flutter](https://github.com/jordansissel/fpm)

> _160k stars_
> ([1 pull request](https://github.com/flutter/flutter/pulls?q=author%3Agamemaker1))

Added a host validation check to the flutter doctor tool.

---

#### [sunbird-rc](https://github.com/sunbird-rc/sunbird-rc-core)

> ([15 pull requests](https://github.com/search?q=involves%3Agamemaker1+org%3Asunbird-rc&type=pullrequests))

Documented process of creating and working with registeries, and created the
[registry-cli](https://npm.im/registry-cli) package to spin up a registry
quickly and easily.

Submitted various RFCs
([1](https://github.com/gamemaker1/electronic-registry-spec),
[2](https://github.com/orgs/Sunbird-RC/discussions/98),
[3](https://github.com/orgs/Sunbird-RC/discussions/99),
[4](https://github.com/Sunbird-RC/community/issues/103)) to improve the project.

---

#### [thecodrr/crayon](https://github.com/thecodrr/crayon)

> _50+ stars_
> ([1 merged pull request](https://github.com/thecodrr/crayon/pulls?q=author%3Agamemaker1))

Updated the library to work with the latest version of V.

---

#### [kiranwells/micro-nord-tc-colors](https://github.com/kiranwells/micro-nord-tc-colors)

> _30+ stars_
> ([1 merged pull request](https://github.com/kiranwells/micro-nord-tc-colors/pulls?q=author%3Agamemaker1))

Added installation guide to the readme.

---

#### [zyedidia/micro](https://github.com/zyedidia/micro)

> _23.7k stars_
> ([1 pull request](https://github.com/micro-editor/plugin-channel/pull/82))

Created a script to automate adding plugins to the official channel.

## Projects That I Have Created

#### [offline-function-calling](https://offline-function-calling.github.io)

> ([contributions](./projects/offline-function-calling))

This project was started as part of my [Google Summer of Code 2025 project with
Google DeepMind](https://summerofcode.withgoogle.com/programs/2025/projects/rexKK7eu).
The primary goal was to explore, extend, and document the function calling
capabilities of the Gemma model family, This effort included benchmarking and
writing tutorials and cookbooks for developers working with offline models like
Gemma 3.

Over 12 weeks, the project progressed from
[simple initial experiments](https://github.com/gamemaker1/gemma3-function-calling-experiments)
to creating a [comprehensive benchmarking suite](https://github.com/offline-function-calling/benchmarks),
to the development of a [function calling SDK](https://github.com/offline-function-calling/sdk)
and a [command-line interface](https://github.com/offline-function-calling/cli)
not unlike the Gemini CLI. This effort included writing and refining
[tutorials](https://github.com/offline-function-calling/sdk/tree/main/docs/learn),
designing and running [benchmarks](https://github.com/offline-function-calling/benchmarks),
and ongoing efforts to support function calling via the Ollama API in Gemma 3.
The goal was to create a set of resources that demonstrates the viability of function
calling with offline, open-source models, and helps developers get started with it.

---

#### [dabbu-knowledge-platform](https://github.com/dabbu-knowledge-platform/cli)

> ([website](https://dabbu-knowledge-platform.github.io))

The Dabbu Knowledge Platform was created with an aim to rethink the way we
organize and traverse large amounts of knowledge, no matter where it is stored.
Dabbu allows you to access any of your personal information (Gmail, Google
Drive, OneDrive, your hard drive, etc.) as simple files and folders from the
Dabbu CLI.

You can also go into the knowledge drive where you can pivot information by
topics/people/places. For example, `k:/$ cd austin` will return you all your
information from Gmail, GDrive, OneDrive that has a reference to the place
Austin. You can further narrow your search by running
`k:/austin$ cd ravi@example.com`. This would show you all emails and files that
are related to Austin and from/to ravi@example.com.

The feature that allows you to organise/search your files based on topics in the
files' text, uses the Latent Dirichlet Algorithm to extract the topics. In the
future, I'd like to generate a one-pager/summary related to a certain set of
topics/places/people. For example, `k:/austin/ravi@example.com$ one-pager`
should give me a neatly organized one pager of all Austin related things I have
discussed with ravi@example.com. This could be tackled using small AI models, or
simple natural language processing.

---

#### [verifiable-presentation/generation-service](https://github.com/verifiable-presentation/spec)

> ([reference impl](https://github.com/verifiable-presentation/impl))

The specification and minimal reference implementation for a plugin-based
service that allows issuers to render verifiable presentations, based on the
[W3C verifiable credential specification](https://www.w3.org/TR/vc-data-model)
from templates, and store it in a queryable database for holders to
list/retrieve.

---

#### [office-text-extractor](https://github.com/gamemaker1/office-text-extractor)

Yet another library to extract text from docx, pptx, xlsx, and pdf files. What
sets it apart is that it parses files based on their mime types, and not their
file extensions. It does not spawn a child process to use a tool installed on
the device, and it reads and returns text from the file if it contains plain
text.

While the parsers for pdf, docx, and xlsx files use popular libraries, the
parser for pptx files is written and maintained by me.

---

#### [yeet](https://github.com/gamemaker1/yeet)

A minimalistic pacman wrapper written in bash.

---

#### [bak](https://github.com/gamemaker1/bak)

A minimalistic backup tool written in bash.

---

#### [tau](https://github.com/gamemaker1/tau)

tiny, adorable urls: a url shortener, written in python using flask and sqlite3.

---

#### [http-negotiator](https://github.com/gamemaker1/http-negotiator)

A HTTP content negotiator for V that allows you to parse the Accept header of an
HTTP request and get the preferred response media type specified by the client.

---

#### [micro-plugin-prettier](https://github.com/gamemaker1/micro-plugin-prettier) and [micro-plugin-xo](https://github.com/gamemaker1/micro-plugin-xo)

Plugins to format and lint code using [Prettier](https://prettier.io) and
[XO](https://github.com/xojs/xo) for my favourite editor,
[Micro](https://micro-editor.github.io).

---

#### [subtitle-translator](https://github.com/gamemaker1/subtitle-translator)

A python that uses Deeplator to translate subtitles in .srt files to and from
six different languages. This project was one of my first open source projects,
and my submission to Google Code-In in 2018.

## Areas of Interest

The following are topics I would like to research in the near future.

- Neurosymbolic AI
- Procedurally generated reinforcement learning environments
- Causal information extraction, and creating knowledge graphs
- Sustainable AI, running inference on edge TPUs and CPUs

The following are areas that I have previously explored and really loved:

- Building custom ROMs for Android phones (compiled LineageOS succesfully for my
  own phone)
- Playing around with low level languages to better understand how the computer
  works (followed tutorials to write a kernel in assembly and rust)
- Multimodal tool/function calling with LLM agents, and benchmarking the
  function calling capabilities of different model sizes and quantizations (did
  this as part of my GSoC project)
- Agent based modelling involving LLMs (worked on applications of this as part
  of my work on AgentTorch)
