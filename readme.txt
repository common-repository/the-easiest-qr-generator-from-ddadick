=== The easiest QR generator from dDadick ===
Contributors: ddadick
Donate link: http://ddadick.prodadi.info/?p=135&lang=en
Tags: QR, tooltip, QRcode image PHP scripts version 0.50i, jQuery Tooltip plugin 1.3, ddadick
Requires at least: 1.0
Tested up to: 1.0
Stable tag: 1.0

QR code image is formed on the screen for reading your mobile phone, etc.

== Description ==

* Used variables qrddadickimgtooltip_call, qrddadickimgtooltip_d, qrddadickimgtooltip_txt.
* For application use tags &lt;qrddadickimgtooltip&gt;TEXT&lt;/qrddadickimgtooltip&gt;.
* If you use tags &lt;qrddadickimgtooltip&gt;TEXT&lt;/qrddadickimgtooltip&gt; without any parameters,
  then as a tooltip will appear QR-code the selected TEXT between
  the tags &lt;qrddadickimgtooltip&gt;TEXT&lt;/qrddadickimgtooltip&gt;.
* If you use tags &lt;qrddadickimgtooltip tooltip=&quot;ToolTipText&quot;;&gt;TEXT&lt;/qrddadickimgtooltip&gt;
  with parameters, as a tooltip will appear QR-code parameter 'tooltip' tag
  &lt;qrddadickimgtooltip tooltip=&quot;ToolTipText&quot;;&gt;TEXT&lt;/qrddadickimgtooltip&gt;.
* Picture QR-code parameter 'tooltip' tag &lt;qrddadickimgtooltip tooltip=&quot;ToolTipText&quot;;&gt;TEXT&lt;/qrddadickimgtooltip&gt;
  in the tooltip that appears to be signed value TEXT.
* In the syntax of the tag &lt;qrddadickimgtooltip tooltip=&quot;ToolTipText&quot;;&gt;TEXT&lt;/qrddadickimgtooltip&gt;
  use of the mark ";" after end of any parameter of the tag is mandatory.
* The presence of the mark " (the quotation marks) is mandatory.
* So far only supports output element tooltipbox.

License

    The easiest QR generator from dDadick
    Copyright (C) 2010-2011  Gubenko Denis Pavlovich

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


    In creating this code is used such software:
    1) QRcode image PHP scripts version 0.50i (C)2000-2009,Y.Swetake (http://www.swetake.com/)
    2) jQuery Tooltip plugin 1.3 (http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/
       and http://docs.jquery.com/Plugins/Tooltip).

    The license "QRcode image PHP scripts version 0.50i" is England is contained in the file
    /qr-ddadick/qr/php/README-e.txt , namely (item 5, Notice):
      "THIS SOFTWARE IS PROVIDED BY Y.Swetake ``AS IS'' AND ANY EXPRESS OR
      IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
      OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
      IN NO EVENT SHALL Y.Swetake OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,
      INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
      (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
      LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)  HOWEVER CAUSED 
      AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
      OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE
      USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE."

    jQuery Tooltip plugin 1.3 is available immediately for two licenses - the MIT and GPL:
      - http://www.opensource.org/licenses/mit-license.php
      - http://www.gnu.org/licenses/gpl.html

    Author plugin "The easiest QR generator from dDadick" thanks developers
    "QRcode image PHP scripts version 0.50i" and "jQuery Tooltip plugin 1.3"
    for the opportunity to use the code "QRcode image PHP scripts version 0.50i"
    and code "jQuery Tooltip plugin 1.3" that is expressed in the licenses
    "QRcode image PHP scripts version 0.50i" and "jQuery Tooltip plugin 1.3", in the draft.

== Installation ==

1. Upload folder /qr-ddadick to the /wp-content/plugins/ directory.
2. Activate the plugin through the 'Plugins' menu in WordPress
3. To use simply insert into your html code tags such as:
   - &lt;qrddadickimgtooltip&gt;TEXT&lt;/qrddadickimgtooltip&gt;;
   - &lt;qrddadickimgtooltip tooltip=&quot;ToolTipText&quot;;&gt;TEXT&lt;/qrddadickimgtooltip&gt;.