---
sidebar: auto
meta:
 - name: keywords
   description: api typescript node.js documentation MultipartFileFilter class
---
# MultipartFileFilter <Badge text="Class" type="class"/>
<!-- Summary -->
<section class="symbol-info"><table class="is-full-width"><tbody><tr><th>Module</th><td><div class="lang-typescript"><span class="token keyword">import</span> { MultipartFileFilter }&nbsp;<span class="token keyword">from</span>&nbsp;<span class="token string">"@tsed/multipartfiles/components/MultipartFileFilter"</span></div></td></tr><tr><th>Source</th><td><a href="https://github.com/Romakita/ts-express-decorators/blob/v4.30.2/src//multipartfiles/components/MultipartFileFilter.ts#L0-L0">/multipartfiles/components/MultipartFileFilter.ts</a></td></tr></tbody></table></section>

<!-- Overview -->
## Overview


<pre><code class="typescript-lang "><span class="token keyword">class</span> MultipartFileFilter <span class="token keyword">implements</span> <a href="/api/common/filters/interfaces/IFilter.html"><span class="token">IFilter</span></a> <span class="token punctuation">{</span>
  <span class="token function">transform</span><span class="token punctuation">(</span>expression<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> request<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> response<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    return request<span class="token punctuation">[</span>"files"<span class="token punctuation">]</span><span class="token punctuation">[</span>0<span class="token punctuation">]</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
<span class="token punctuation">}</span></code></pre>



<!-- Members -->




## Members


::: v-pre

<div class="method-overview">
<pre><code class="typescript-lang "><span class="token function">transform</span><span class="token punctuation">(</span>expression<span class="token punctuation">:</span> <span class="token keyword">string</span><span class="token punctuation">,</span> request<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">,</span> response<span class="token punctuation">:</span> <span class="token keyword">any</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
 return request<span class="token punctuation">[</span>"files"<span class="token punctuation">]</span><span class="token punctuation">[</span>0<span class="token punctuation">]</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span></code></pre>

</div>



:::