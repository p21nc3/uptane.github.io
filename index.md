![Uptane logo](https://raw.githubusercontent.com/uptane/uptane.github.io/master/logo.png)

# Description

Software update systems for automobiles promise huge benefits at the cost of potential security vulnerabilities. No existing solution considers more advanced security objectives such as resilience against a repository compromise, selective blocking of update traffic by a MITM, or compromise at a supplier’s site.

To address this, we designed Uptane, a software update framework for automobiles that counters a comprehensive array of security attacks and that is resilient to partial compromises. Uptane addresses automotive specific vulnerabilities and limitations. Uptane is flexible and easy to adopt for industry stakeholders. Design details were developed together with the main automotive industry stakeholders in the USA.

In a future demonstration, we will show various attack scenarios, and how the attacks are prevented by Uptane.

Uptane is a collaboration between the New York University Tandon School of Engineering (NYU), the University of Michigan's Transport Research Institute (UMTRI), and the Southwest Research Institute (SWRI).

# Open call for security review

We invite all security researchers and academics to perform a security review of Uptane.

We want to hear from you about ways that you could exploit Uptane. 
For instance, you may find a way that an attacker could replay old images to ECUs because the message signature doesn't cover the right content.
You can help to fix security issues before hackers use them to exploit  millions of cars!

Please send us your questions, comments, and findings to the [public mailing list](https://groups.google.com/forum/#!forum/uptane-discussion).

We are also interested in hearing about security problems in our Reference Implementation.
While we do not expect cars  to use this code directly, errors in this software may be  duplicated by production implementations.
Please report these using our GitHub issue tracker.

# Academic publications

* Uptane: Securing Software Updates for Automobiles ([PDF](https://isis.poly.edu/~jcappos/papers/kuppusamy_escar_16.pdf) / [Video](https://www.youtube.com/watch?v=nDghHNxRGHA) / [Slides](https://docs.google.com/presentation/d/17bl_-y3U78xbhaTbsZDu_Uv0zI9UAKZ8v78dj55yC3k/edit?usp=sharing)). Published in the proceedings of the 14th escar europe (2016).

# Technical documents and source code

* [Design Overview](https://docs.google.com/document/d/1pBK--40BCg_ofww4GES0weYFB6tZRedAjUy6PJ4Rgzk/edit?usp=sharing)
* [Implementation Specification](https://docs.google.com/document/d/1wjg3hl0iDLNh7jIRaHl3IXhwm0ssOtDje5NemyTBcaw/edit?usp=sharing)
* [Deployment Considerations](https://docs.google.com/document/d/17wOs-T7mugwte5_Dt-KLGMsp-3_yAARejpFmrAMefSE/edit?usp=sharing)
* [Reference Implementation](https://github.com/uptane/uptane)

# Slides from last workshop

* [SOTA #4: Design Overview](https://docs.google.com/presentation/d/1YiN5AKbjDZjnu0L1NpNLLroIkRuyuClA2UNYOLkT5oc/edit?usp=sharing)
* [SOTA #4: Implementation Specification](https://docs.google.com/presentation/d/1f3DdpXvU3oT8zygTfrlJeaNDjdbBHHz49lKYHAUF3PQ/edit?usp=sharing)
* [SOTA #4: Deployment Considerations](https://docs.google.com/presentation/d/1vwPHl1RtMM9y1GfRbkML8AHWbThkIOCPMbO006JEIYk/edit?usp=sharing)

# Participation

* [Public mailing list](https://groups.google.com/forum/#!forum/uptane-discussion)
* [Private discussion forum for OEMs and suppliers (by invitation only)](https://uptane.umtri.umich.edu/forum/)

# Press

* [How Uptane Can Protect Your Car From Hackers](https://www.facebook.com/Reuters/videos/1364617036891982/)
* [Are software updates key to stopping criminal car hacks?](http://www.csmonitor.com/World/Passcode/2017/0118/Are-software-updates-key-to-stopping-criminal-car-hacks) [[Yahoo!]](https://www.yahoo.com/news/software-updates-key-stopping-criminal-car-hacks-174510573.html)
* [Call Issued to White Hat Hackers: Find the Flaws in New Automotive Software Updater](http://engineering.nyu.edu/press-releases/2017/01/18/call-issued-white-hat-hackers-find-flaws-new-automotive-software-updater) [[Yahoo!]](https://www.yahoo.com/tech/call-issued-white-hat-hackers-flaws-automotive-software-050100383.html) [[News9]](http://www.news9.com/story/34283886/call-issued-to-white-hat-hackers-find-the-flaws-in-new-automotive-software-updater)

# Acknowledgements

Uptane is supported by U.S. Department of Homeland Security grants D15PC00239 and D15PC00302.

# Disclaimer

The views and conclusions contained herein are the authors’ and should not be interpreted as necessarily representing the official policies or endorsements, either expressed or implied, of the US Department of Homeland Security (DHS) or the US government.