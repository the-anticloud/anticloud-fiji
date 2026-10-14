# FIJI

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-scientific_lab-lightgrey)

> Anticloud-hardened packaging of the upstream project `FIJI` in category **SCIENTIFIC LAB**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SCIENTIFIC LAB · **Upstream:** https://github.com/fiji/fiji · **Upstream pin:** `1a914a280efda634307cd3e9cc8d6f14e1913412` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

[![](https://github.com/fiji/fiji/actions/workflows/build.yml/badge.svg)](https://github.com/fiji/fiji/actions/workflows/build.yml)
[![developer chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://imagesc.zulipchat.com/#narrow/stream/327238-Fiji)
[![Image.sc Forum](https://img.shields.io/badge/dynamic/json.svg?label=forum&amp;url=https%3A%2F%2Fforum.image.sc%2Ftags%2Ffiji.json&amp;query=%24.topic_list.tags.0.topic_count&amp;colorB=green&amp;&amp;suffix=%20topics&amp;logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABPklEQVR42m3SyyqFURTA8Y2BER0TDyExZ+aSPIKUlPIITFzKeQWXwhBlQrmFgUzMMFLKZeguBu5y+//17dP3nc5vuPdee6299gohUYYaDGOyyACq4JmQVoFujOMR77hNfOAGM+hBOQqB9TjHD36xhAa04RCuuXeKOvwHVWIKL9jCK2bRiV284QgL8MwEjAneeo9VNOEaBhzALGtoRy02cIcWhE34jj5YxgW+E5Z4iTPkMYpPLCNY3hdOYEfNbKYdmNngZ1jyEzw7h7AIb3fRTQ95OAZ6yQpGYHMMtOTgouktYwxuXsHgWLLl+4x++Kx1FJrjLTagA77bTPvYgw1rRqY56e+w7GNYsqX6JfPwi7aR+Y5SA+BXtKIRfkfJAYgj14tpOF6+I46c4/cAM3UhM3JxyKsxiOIhH0IO6SH/A1Kb1WBeUjbkAAAAAElFTkSuQmCC)](https://forum.image.sc/tag/fiji)

[ Fiji Is Just ImageJ ]
=======================

Fiji is a "batteries-included" distribution of
[ImageJ](http://imagej.net/)—a popular, free scientific image processing
application—which includes a lot of plugins organized into a coherent
menu structure. Fiji compares to ImageJ as Ubuntu compares to Linux.

The main focus of Fiji is to assist research in life sciences.

At the moment, the following platforms are supported:

- Windows arm64 and x64
- Linux arm64 and x64
- macOS arm64 and x64
- all platforms supporting Java 21+ and a POSIX shell, via `fiji.sh`

The setup is as easy as unpacking the portable archive and
double-clicking the [ImageJ
launcher](https://github.com/imagej/imagej-launcher).

Fiji is intended to be the most painless, easy, quick and convenient way
to install ImageJ and plugins and keep everything up-to-date.

Usage
-----

Fiji is meant to be distributed without source, to make the download as
small as possible. In the basic version, Fiji is a portable application,
i.e. it should run wherever you copy it.

The starting point is the Fiji launcher, which will launch Java, set
up the environment, and call ImageJ/ImageJ2.

To pass arguments to ImageJ, just specify them on the command line.

To pass arguments to the Java Virtual Machine, specify them on the
command line, separating them from the ImageJ arguments (if any) with a
`--`.  In other words, if you want to override the memory setting, call
Fiji like this:

	$ ./fiji -Xmx128m --

Open Source
-----------

We are dedicated to open source. Not only does open source allow other
developers to port the application to new platforms that the original
authors did not begin to think of, it allows scientists to study the
code to understand the inner workings of the algorithms used, and it
permits others to use the program in totally new ways, and enhance it in
all imaginable ways.

Therefore, the majority of Fiji is licensed under the GNU Public License
version 2. Exceptions are listed in the
[LICENSES](https://github.com/fiji/fiji/blob/main/LICENSES) file.

Fiji's source code is split up into a [main
project](https://github.com/fiji/fiji), containing the top-level project and
support scripts, while all components live in their own projects in the
[Fiji organization on GitHub](https://github.com/fiji/). As a rule of thumb: the
file name and the project name correspond pretty well, e.g. fiji-lib.jar is
maintained in [fiji-lib](https://github.com/fiji/fiji-lib).

Participating
-------------

[Pull Requests](https://help.github.com/articles/using-pull-requests)
are very welcome!

See the [Contributing](http://imagej.net/Contributing) page of the ImageJ wiki.

Authors
-------

* Fiji was created by
  [Johannes Schindelin](https://imagej.net/people/dscho).
  It is currently maintained by [Curtis Rueden](https://imagej.net/people/ctrueden)
  of [LOCI](https://imagej.net/orgs/loci) at the University of Wisconsin-Madison.
* ImageJ was created and is maintained by
  [Wayne Rasband](https://imagej.net/people/rasband).
* ImageJ2 was created and is maintained by Curtis Rueden.
* For a list of most recent contributors, please refer to the
  [Contributors](http://imagej.net/people) page of the ImageJ wiki.

Thanks
------

We are very grateful to Wayne Rasband, who is not only a very dedicated
developer of ImageJ; he also fosters an active and friendly
community around ImageJ.

We are especially grateful to be part of an outstanding
[community](http://imagej.net/discuss) who is active, friendly and
helping to scientists understanding and analysing images every day.

Oh, and Fiji is also an island. We just wanted to let you know.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Java / Maven** (manifests: pom.xml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `Contents/`, `bin/`, `config/`, `images/`, `luts/`, `macros/`, `matlab/`, `plugins/`, `resources/`, `scripts/`, `src/`
- Snapshot size: **234 files**, **10452 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (37), `.lut` (36), `.sh` (30), `.bsh` (24), `.java` (19), `.txt` (16)
- Upstream commit pinned for this packaging: `1a914a280efda634307cd3e9cc8d6f14e1913412`

---

## Installation

[![developer chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://imagesc.zulipchat.com/#narrow/stream/327238-Fiji)
[![Image.sc Forum](https://img.shields.io/badge/dynamic/json.svg?label=forum&amp;url=https%3A%2F%2Fforum.image.sc%2Ftags%2Ffiji.json&amp;query=%24.topic_list.tags.0.topic_count&amp;colorB=green&amp;&amp;suffix=%20topics&amp;logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABPklEQVR42m3SyyqFURTA8Y2BER0TDyExZ+aSPIKUlPIITFzKeQWXwhBlQrmFgUzMMFLKZeguBu5y+//17dP3nc5vuPdee6299gohUYYaDGOyyACq4JmQVoFujOMR77hNfOAGM+hBOQqB9TjHD36xhAa04RCuuXeKOvwHVWIKL9jCK2bRiV284QgL8MwEjAneeo9VNOEaBhzALGtoRy02cIcWhE34jj5YxgW+E5Z4iTPkMYpPLCNY3hdOYEfNbKYdmNngZ1jyEzw7h7AIb3fRTQ95OAZ6yQpGYHMMtOTgouktYwxuXsHgWLLl+4x++Kx1FJrjLTagA77bTPvYgw1rRqY56e+w7GNYsqX6JfPwi7aR+Y5SA+BXtKIRfkfJAYgj14tpOF6+I46c4/cAM3UhM3JxyKsxiOIhH0IO6SH/A1Kb1WBeUjbkAAAAAElFTkSuQmCC)](https://forum.image.sc/tag/fiji)

[ Fiji Is Just ImageJ ]
=======================

Fiji is a "batteries-included" distribution of
[ImageJ](http://imagej.net/)—a popular, free scientific image processing
application—which includes a lot of plugins organized into a coherent
menu structure. Fiji compares to ImageJ as Ubuntu compares to Linux.

The main focus of Fiji is to assist research in life sciences.

At the moment, the following platforms are supported:

- Windows arm64 and x64
- Linux arm64 and x64
- macOS arm64 and x64
- all platforms supporting Java 21+ and a POSIX shell, via `fiji.sh`

The setup is as easy as unpacking the portable archive and
double-clicking the [ImageJ
launcher](https://github.com/imagej/imagej-launcher).

Fiji is intended to be the most painless, easy, quick and convenient way
to install ImageJ and plugins and keep everything up-to-date.

Usage
-----

Fiji is meant to be distributed without source, to make the download as
small as possible. In the basic version, Fiji is a portable application,
i.e. it should run wherever you copy it.

The starting point is the Fiji launcher, which will launch Java, set
up the environment, and call ImageJ/ImageJ2.

To pass arguments to ImageJ, just specify them on the command line.

To pass arguments to the Java Virtual Machine, specify them on the
command line, separating them from the ImageJ arguments (if any) with a
`--`.  In other words, if you want to override the memory setting, call
Fiji like this:

	$ ./fiji -Xmx128m --

Open Source
-----------

We are dedicated to open source. Not only does open source allow other
developers to port the application to new platforms that the original
authors did not begin to think of, it allows scientists to study the
code to understand the inner workings of the algorithms used, and it
permits others to use the program in totally new ways, and enhance it in
all imaginable ways.

Therefore, the majority of Fiji is licensed under the GNU Public License
version 2. Exceptions are listed in the
[LICENSES](https://github.com/fiji/fiji/blob/main/LICENSES) file.

Fiji's source code is split up into a [main
project](https://github.com/fiji/fiji), containing the top-level project and
support scripts, while all components live in their own projects in the
[Fiji organization on GitHub](https://github.com/fiji/). As a rule of thumb: the
file name and the project name correspond pretty well, e.g. fiji-lib.jar is
maintained in [fiji-lib](https://github.com/fiji/fiji-lib).

Participating
-------------

[Pull Requests](https://help.github.com/articles/using-pull-requests)
are very welcome!

See the [Contributing](http://imagej.net/Contributing) page of the ImageJ wiki.

Authors
-------

* Fiji was created by
  [Johannes Schindelin](https://imagej.net/people/dscho).
  It is currently maintained by [Curtis Rueden](https://imagej.net/people/ctrueden)
  of [LOCI](https://imagej.net/orgs/loci) at the University of Wisconsin-Madison.
* ImageJ was created and is maintained by
  [Wayne Rasband](https://imagej.net/people/rasband).
* ImageJ2 was created and is maintained by Curtis Rueden.
* For a list of most recent contributors, please refer to the
  [Contributors](http://imagej.net/people) page of the ImageJ wiki.

Thanks
------

We are very grateful to Wayne Rasband, who is not only a very dedicated
developer of ImageJ; he also fosters an active and friendly
community around ImageJ.

We are especially grateful to be part of an outstanding
[community](http://imagej.net/discuss) who is active, friendly and
helping to scientists understanding and analysing images every day.

Oh, and Fiji is also an island. We just wanted to let you know.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

-----

Fiji is meant to be distributed without source, to make the download as
small as possible. In the basic version, Fiji is a portable application,
i.e. it should run wherever you copy it.

The starting point is the Fiji launcher, which will launch Java, set
up the environment, and call ImageJ/ImageJ2.

To pass arguments to ImageJ, just specify them on the command line.

To pass arguments to the Java Virtual Machine, specify them on the
command line, separating them from the ImageJ arguments (if any) with a
`--`.  In other words, if you want to override the memory setting, call
Fiji like this:

	$ ./fiji -Xmx128m --

Open Source
-----------

We are dedicated to open source. Not only does open source allow other
developers to port the application to new platforms that the original
authors did not begin to think of, it allows scientists to study the
code to understand the inner workings of the algorithms used, and it
permits others to use the program in totally new ways, and enhance it in
all imaginable ways.

Therefore, the majority of Fiji is licensed under the GNU Public License
version 2. Exceptions are listed in the
[LICENSES](https://github.com/fiji/fiji/blob/main/LICENSES) file.

Fiji's source code is split up into a [main
project](https://github.com/fiji/fiji), containing the top-level project and
support scripts, while all components live in their own projects in the
[Fiji organization on GitHub](https://github.com/fiji/). As a rule of thumb: the
file name and the project name correspond pretty well, e.g. fiji-lib.jar is
maintained in [fiji-lib](https://github.com/fiji/fiji-lib).

Participating
-------------

[Pull Requests](https://help.github.com/articles/using-pull-requests)
are very welcome!

See the [Contributing](http://imagej.net/Contributing) page of the ImageJ wiki.

Authors
-------

* Fiji was created by
  [Johannes Schindelin](https://imagej.net/people/dscho).
  It is currently maintained by [Curtis Rueden](https://imagej.net/people/ctrueden)
  of [LOCI](https://imagej.net/orgs/loci) at the University of Wisconsin-Madison.
* ImageJ was created and is maintained by
  [Wayne Rasband](https://imagej.net/people/rasband).
* ImageJ2 was created and is maintained by Curtis Rueden.
* For a list of most recent contributors, please refer to the
  [Contributors](http://imagej.net/people) page of the ImageJ wiki.

Thanks
------

We are very grateful to Wayne Rasband, who is not only a very dedicated
developer of ImageJ; he also fosters an active and friendly
community around ImageJ.

We are especially grateful to be part of an outstanding
[community](http://imagej.net/discuss) who is active, friendly and
helping to scientists understanding and analysing images every day.

Oh, and Fiji is also an island. We just wanted to let you know.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

launcher](https://github.com/imagej/imagej-launcher).

Fiji is intended to be the most painless, easy, quick and convenient way
to install ImageJ and plugins and keep everything up-to-date.

Usage
-----

Fiji is meant to be distributed without source, to make the download as
small as possible. In the basic version, Fiji is a portable application,
i.e. it should run wherever you copy it.

The starting point is the Fiji launcher, which will launch Java, set
up the environment, and call ImageJ/ImageJ2.

To pass arguments to ImageJ, just specify them on the command line.

To pass arguments to the Java Virtual Machine, specify them on the
command line, separating them from the ImageJ arguments (if any) with a
`--`.  In other words, if you want to override the memory setting, call
Fiji like this:

	$ ./fiji -Xmx128m --

Open Source
-----------

We are dedicated to open source. Not only does open source allow other
developers to port the application to new platforms that the original
authors did not begin to think of, it allows scientists to study the
code to understand the inner workings of the algorithms used, and it
permits others to use the program in totally new ways, and enhance it in
all imaginable ways.

Therefore, the majority of Fiji is licensed under the GNU Public License
version 2. Exceptions are listed in the
[LICENSES](https://github.com/fiji/fiji/blob/main/LICENSES) file.

Fiji's source code is split up into a [main
project](https://github.com/fiji/fiji), containing the top-level project and
support scripts, while all components live in their own projects in the
[Fiji organization on GitHub](https://github.com/fiji/). As a rule of thumb: the
file name and the project name correspond pretty well, e.g. fiji-lib.jar is
maintained in [fiji-lib](https://github.com/fiji/fiji-lib).

Participating
-------------

[Pull Requests](https://help.github.com/articles/using-pull-requests)
are very welcome!

See the [Contributing](http://imagej.net/Contributing) page of the ImageJ wiki.

Authors
-------

* Fiji was created by
  [Johannes Schindelin](https://imagej.net/people/dscho).
  It is currently maintained by [Curtis Rueden](https://imagej.net/people/ctrueden)
  of [LOCI](https://imagej.net/orgs/loci) at the University of Wisconsin-Madison.
* ImageJ was created and is maintained by
  [Wayne Rasband](https://imagej.net/people/rasband).
* ImageJ2 was created and is maintained by Curtis Rueden.
* For a list of most recent contributors, please refer to the
  [Contributors](http://imagej.net/people) page of the ImageJ wiki.

Thanks
------

We are very grateful to Wayne Rasband, who is not only a very dedicated
developer of ImageJ; he also fosters an active and friendly
community around ImageJ.

We are especially grateful to be part of an outstanding
[community](http://imagej.net/discuss) who is active, friendly and
helping to scientists understanding and analysing images every day.

Oh, and Fiji is also an island. We just wanted to let you know.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Java / Maven |
| Manifests detected | pom.xml |
| Files in snapshot | 234 |
| Lines of code | 10452 |
| Dependency references | 16 |
| Dependencies by ecosystem | conda: 16 |
| Upstream license | GPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| conda | based | - | config/environment.yml |
| conda | conda-forge | - | config/environment.yml |
| conda | python | 3.12 | config/environment.yml |
| conda | pip | - | config/environment.yml |
| conda | pip | - | config/environment.yml |
| conda | process | - | config/environment.yml |
| conda | pyimagej | - | config/environment.yml |
| conda | appose | - | config/environment.yml |
| conda | java-awt-and-python-qt | - | config/environment.yml |
| conda | PyQt6 | - | config/environment.yml |
| conda | QtPy | - | config/environment.yml |
| conda | based | - | config/environment.yml |
| conda | scikit-image | - | config/environment.yml |
| conda | napari | - | config/environment.yml |
| conda | napari-imagej | - | config/environment.yml |
| ... | (1 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

To pass arguments to ImageJ, just specify them on the command line.

To pass arguments to the Java Virtual Machine, specify them on the
command line, separating them from the ImageJ arguments (if any) with a
`--`.  In other words, if you want to override the memory setting, call
Fiji like this:

	$ ./fiji -Xmx128m --

Open Source
-----------

We are dedicated to open source. Not only does open source allow other
developers to port the application to new platforms that the original
authors did not begin to think of, it allows scientists to study the
code to understand the inner workings of the algorithms used, and it
permits others to use the program in totally new ways, and enhance it in
all imaginable ways.

Therefore, the majority of Fiji is licensed under the GNU Public License
version 2. Exceptions are listed in the
[LICENSES](https://github.com/fiji/fiji/blob/main/LICENSES) file.

Fiji's source code is split up into a [main
project](https://github.com/fiji/fiji), containing the top-level project and
support scripts, while all components live in their own projects in the
[Fiji organization on GitHub](https://github.com/fiji/). As a rule of thumb: the
file name and the project name correspond pretty well, e.g. fiji-lib.jar is
maintained in [fiji-lib](https://github.com/fiji/fiji-lib).

Participating
-------------

[Pull Requests](https://help.github.com/articles/using-pull-requests)
are very welcome!

See the [Contributing](http://imagej.net/Contributing) page of the ImageJ wiki.

Authors
-------

* Fiji was created by
  [Johannes Schindelin](https://imagej.net/people/dscho).
  It is currently maintained by [Curtis Rueden](https://imagej.net/people/ctrueden)
  of [LOCI](https://imagej.net/orgs/loci) at the University of Wisconsin-Madison.
* ImageJ was created and is maintained by
  [Wayne Rasband](https://imagej.net/people/rasband).
* ImageJ2 was created and is maintained by Curtis Rueden.
* For a list of most recent contributors, please refer to the
  [Contributors](http://imagej.net/people) page of the ImageJ wiki.

Thanks
------

We are very grateful to Wayne Rasband, who is not only a very dedicated
developer of ImageJ; he also fosters an active and friendly
community around ImageJ.

We are especially grateful to be part of an outstanding
[community](http://imagej.net/discuss) who is active, friendly and
helping to scientists understanding and analysing images every day.

Oh, and Fiji is also an island. We just wanted to let you know.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `FIJI` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: GPL-3.0** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU General Public License is a free, copyleft license for
software and other kinds of works.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
the GNU General Public License is intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.  We, the Free Software Foundation, use the
GNU General Public License for most of our software; it applies also to
any other work released this way by its authors.  You can apply it to
your programs, too.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original GPL-3.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `GPL-3.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `FIJI` (category: SCIENTIFIC LAB)
- **Upstream URL:** https://github.com/fiji/fiji
- **Pinned commit (SHA):** `1a914a280efda634307cd3e9cc8d6f14e1913412`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`2e3dfb04c999957c0a90b726f5107e117d680bf9ea685f19da4eb147c052a7db`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

