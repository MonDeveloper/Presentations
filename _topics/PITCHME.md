### LEVEL 2-A

  - Offers the full scientific computing power of the R programming language
  - Within Spark batch and streaming apps on the JVM

---

### LEVEL 2-B

<ol>
<li class="fragment" data-fragment-index="1">New `analyze` operation on RDD[<span style="color:gray">OCPUTask</span>]</li>
<li class="fragment" data-fragment-index="2">This operation executes R analytics on OpenCPU</li>
<li class="fragment" data-fragment-index="3">And generates RDD[<span style="color:gray">OCPUResult</span>]</li>
</ol>

<span class="fragment" data-fragment-index="4" style="font-size: 0.8em; color:gray">The ROSE API is built on top of the <a target="_blank" href="https://github.com/onetapbeyond/opencpu-r-executor">opencpu-r-executor</a> library.</span>

---?include=./_topics/eventsourcing.md
