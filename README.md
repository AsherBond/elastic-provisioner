elastic-provisioner
===================

A DevOpsy PaaS for distributed systems developers, teaching the ways of Test-Driven DevOps Design and Continuous Automation. GitStrapped provides an interoperability framework for runtime bootstrapping of (para)virtual machinery as well as physical machinery if that's what you're into.

Installation is quite simple:
curl -s -1 -k https://gitstrapped.elasticprovisioner.com/install-gitstrapped | bash

Once the client is installed, packages can be found and then installed in a single command:
ep-gitstrapped search <package>
ep-gitstrapped install <pkg-mask>

Please read the License (AGPL v3)
http://gitstrapped.elasticprovisioner.com/LICENSE-AGPLv3.txt
or
https://www.gnu.org/licenses/agpl-3.0.de.html

A STRAP is a Service Template Running A Process
A single STRAP may be licensed to the public under AGPLv3 or a more permissive license such as LGPL or BSD or GNU or Apache License.
A provisioner may invoke the STRAP at his or her own risk via ep-gitstrapped <strap>

