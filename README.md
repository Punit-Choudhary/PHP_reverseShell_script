# PHP_reverseShell_script
# php-reverse-shell - A Reverse Shell implementation in PHP.  Copyright (C) 2007 pentestmonkey@pentestmonkey.net

This tool may be used for legal purposes only.  Users take full responsibility<br />
for any actions performed using this tool.  The author accepts no liability
for damage caused by this tool.  If these terms are not acceptable to you, then
do not use this tool.
<br />
In all other respects the GPL version 2 applies:<br />
<br />
This program is free software; you can redistribute it and/or modify<br />
it under the terms of the GNU General Public License version 2 as<br />
published by the Free Software Foundation.
<br />
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.<br />  See the
GNU General Public License for more details.<br />
<br />
You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.<br />
<br />
This tool may be used for legal purposes only.  Users take full responsibility
for any actions performed using this tool.  If these terms are not acceptable to
you, then do not use this tool.<br />
<br />
You are encouraged to send comments, improvements or suggestions to
me at pentestmonkey@pentestmonkey.net<br />
<br />
Description<br />
-----------<br />
This script will make an outbound TCP connection to a hardcoded IP and port.<br />
The recipient will be given a shell running as the current user (apache normally).<br />
<br />
Limitations<br />
-----------<br />
proc_open and stream_set_blocking require PHP version 4.3+, or 5+<br />
Use of stream_select() on file descriptors returned by proc_open() will fail and return FALSE under Windows.<br />
Some compile-time options are needed for daemonisation (like pcntl, posix).  These are rarely available.<br />
<br />
http://pentestmonkey.net/tools/php-reverse-shell incase you stuck.<br />
