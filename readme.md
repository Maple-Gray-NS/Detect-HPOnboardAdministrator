A small utility to detect if the HP Onboard Admin interface is in use and running on an outdated system.

## Usage

```
python3 DetectHPOboardAdmin.py

Usage: python3 DetectHPOboardAdmin.py https://<targetIP>/hpoa
```

```
python DetectHPOboardAdmin.py https://127.0.0.1/hpoa

[TRUNCATED]
                                <hpoa:version>3.70</hpoa:version>
                                <hpoa:manufacturer>HP</hpoa:manufacturer>
                                <hpoa:name>HP Insight Onboard Administrator SOAP Interface</hpoa:name>
                                <hpoa:compiledDateTime>2012-10-01T23:36:17Z</hpoa:compiledDateTime>
                                <hpoa:credits>Copyright 2006 Hewlett-Packard Development Company, L.P.&#xA;TWP,RMU&#xA;&#xA;&#xA;Part of the software embedded in this product is gSOAP software.&#xA;&#xA;Portions created by gSOAP are Copyright (C) 2001-2004 Robert A. van Engelen, Genivia inc. All Rights Reserved.&#xA;&#xA;THE SOFTWARE IN THIS PRODUCT WAS IN PART PROVIDED BY GENIVIA INC AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.</hpoa:credits>
[TRUNCATED]
```
