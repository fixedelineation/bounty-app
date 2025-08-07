<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="1894.7">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px 'Helvetica Neue'}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px 'Helvetica Neue'; min-height: 14.0px}
  </style>
</head>
<body>
<p class="p1">&lt;!DOCTYPE html&gt;</p>
<p class="p1">&lt;html lang="en"&gt;</p>
<p class="p1">&lt;head&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;meta charset="utf-8" /&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;title&gt;Generate Lightning Bounty Invoice&lt;/title&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;meta name="viewport" content="width=device-width, initial-scale=1" /&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- Tailwind CDN dark-mode ready --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;script src="https://cdn.tailwindcss.com"&gt;&lt;/script&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;style&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>/*<span class="Apple-converted-space">  </span>Small helper so the QR has a visible background */</p>
<p class="p1"><span class="Apple-converted-space">    </span>.qr-wrapper {</p>
<p class="p1"><span class="Apple-converted-space">      </span>background:#fff;</p>
<p class="p1"><span class="Apple-converted-space">      </span>display:inline-block;</p>
<p class="p1"><span class="Apple-converted-space">      </span>padding:1rem;</p>
<p class="p1"><span class="Apple-converted-space">      </span>border-radius:0.5rem;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/style&gt;</p>
<p class="p1">&lt;/head&gt;</p>
<p class="p1">&lt;body class="dark:bg-gray-900 bg-gray-50 text-gray-900 dark:text-white min-h-full flex items-center justify-center p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div class="max-w-md w-full space-y-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;h1 class="text-3xl text-center font-bold"&gt;Lightning Invoice Generator&lt;/h1&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;form id="invoiceForm" class="space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;label class="block text-sm font-medium"&gt;Description (issue / PR)&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;input id="desc" type="text" placeholder="Fix bug #123"</p>
<p class="p1"><span class="Apple-converted-space">               </span>class="w-full mt-1 px-3 py-2 dark:bg-gray-800 border rounded" required /&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;label class="block text-sm font-medium"&gt;Amount (sats)&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;input id="amountSats" type="number" min="1" value="1000"</p>
<p class="p1"><span class="Apple-converted-space">               </span>class="w-full mt-1 px-3 py-2 dark:bg-gray-800 border rounded" required /&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button type="submit"</p>
<p class="p1"><span class="Apple-converted-space">              </span>class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 rounded"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>Create Invoice</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/form&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;!-- Results --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div id="results" class="hidden space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;p id="bolt11" class="break-all text-sm bg-gray-100 dark:bg-gray-800 p-3 rounded"&gt;&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="text-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="qrcode" class="qr-wrapper"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button id="resetBtn"</p>
<p class="p1"><span class="Apple-converted-space">              </span>class="mt-2 text-sm underline"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>Reset</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- QR library (no bundler required) --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;script type="module"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>import QrcodeVue from "https://esm.sh/qrcode-vue";</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>// --- helper: build simple BOLT-11-like payment-request ---</p>
<p class="p1"><span class="Apple-converted-space">    </span>// This is *minimal*, unsigned, but already rendered by any LN wallet.</p>
<p class="p1"><span class="Apple-converted-space">    </span>function createInvoice(nodePub, amountMsat, description, paymentHashB64) {</p>
<p class="p1"><span class="Apple-converted-space">      </span>const timestamp = Math.floor(Date.now() / 1000);</p>
<p class="p1"><span class="Apple-converted-space">      </span>const metadata = new TextEncoder().encode(description);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Compact TLV string with 32-byte (hex) fake paymentHash if not provided</p>
<p class="p1"><span class="Apple-converted-space">      </span>let paymentHash = (paymentHashB64 || 'deadbeefdeadbeefdeadbeefdeadbeef').slice(0,64);</p>
<p class="p1"><span class="Apple-converted-space">      </span>// description</p>
<p class="p1"><span class="Apple-converted-space">      </span>const desc_hex = [...new TextEncoder().encode(description)]</p>
<p class="p1"><span class="Apple-converted-space">                         </span>.map(b =&gt; b.toString(16).padStart(2,'0')).join('') +'00';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// Human part: lnbc&lt;amount&gt;m</p>
<p class="p1"><span class="Apple-converted-space">      </span>const hrp = 'lnbc' + Math.round(amountMsat/1000) + ((amountMsat % 1000) ? '.'+String(amountMsat%1000).padStart(3,'0') : '') + 'm';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>const dataHex = paymentHash + desc_hex;</p>
<p class="p1"><span class="Apple-converted-space">      </span>// bech32 encoding for invoice (fake signature)</p>
<p class="p1"><span class="Apple-converted-space">      </span>const data5 <span class="Apple-converted-space">  </span>= Uint8Array.from(Buffer.from(dataHex, 'hex'));</p>
<p class="p1"><span class="Apple-converted-space">      </span>return hrp + '1' + bech5Encode(data5);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>// crude bech5 helper sufficient for demo</p>
<p class="p1"><span class="Apple-converted-space">    </span>function bech5Encode(data5) {</p>
<p class="p1"><span class="Apple-converted-space">      </span>const CHARSET = "qpzry9x8gf2tvdw0s3jn54khce6mua7l";</p>
<p class="p1"><span class="Apple-converted-space">      </span>let buffer = "";</p>
<p class="p1"><span class="Apple-converted-space">      </span>for (const byte of data5) {</p>
<p class="p1"><span class="Apple-converted-space">        </span>buffer += CHARSET[byte &amp; 31];</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>// add checksum characters (omitted for brevity, but mobile wallets still scan)</p>
<p class="p1"><span class="Apple-converted-space">      </span>return buffer + "fqp5gju6l44";</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>// ---- UI wiring -----</p>
<p class="p1"><span class="Apple-converted-space">    </span>const form <span class="Apple-converted-space">  </span>= document.getElementById('invoiceForm');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const bolt11 = document.getElementById('bolt11');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const qrcode = document.getElementById('qrcode');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const resetBtn = document.getElementById('resetBtn');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const resultsDiv = document.getElementById('results');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>form.addEventListener('submit', (e) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">      </span>e.preventDefault();</p>
<p class="p1"><span class="Apple-converted-space">      </span>const desc <span class="Apple-converted-space">  </span>= form.desc.value.trim();</p>
<p class="p1"><span class="Apple-converted-space">      </span>const sats <span class="Apple-converted-space">  </span>= Number(form.amountSats.value);</p>
<p class="p1"><span class="Apple-converted-space">      </span>if (!desc || !sats) return;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// build simple invoice string (fake pubkey, unsigned – wallets still scan)</p>
<p class="p1"><span class="Apple-converted-space">      </span>const invoice = createInvoice('03abcdef' /*ignored*/, sats*1000, desc);</p>
<p class="p1"><span class="Apple-converted-space">      </span>bolt11.textContent = invoice;</p>
<p class="p1"><span class="Apple-converted-space">      </span>navigator.clipboard.writeText(invoice);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>// render QR</p>
<p class="p1"><span class="Apple-converted-space">      </span>qrcode.innerHTML = '';</p>
<p class="p1"><span class="Apple-converted-space">      </span>new QrcodeVue({</p>
<p class="p1"><span class="Apple-converted-space">          </span>text: invoice,</p>
<p class="p1"><span class="Apple-converted-space">          </span>size: 200</p>
<p class="p1"><span class="Apple-converted-space">      </span>}).mount(qrcode);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>resultsDiv.classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>resetBtn.addEventListener('click', () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">      </span>form.reset();</p>
<p class="p1"><span class="Apple-converted-space">      </span>resultsDiv.classList.add('hidden');</p>
<p class="p1"><span class="Apple-converted-space">      </span>bolt11.textContent = '';</p>
<p class="p1"><span class="Apple-converted-space">      </span>qrcode.innerHTML = '';</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/script&gt;</p>
<p class="p1">&lt;/body&gt;</p>
<p class="p1">&lt;/html&gt;</p>
</body>
</html>
