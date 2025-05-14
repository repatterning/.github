**Links**

* [The Artificial Intelligence Unit](https://github.com/theartificialintelligenceunit)

<br>

```mermaid
stateDiagram-v2
    state director <<fork>>
      [*] --> daily
      daily --> structures
      structures --> director
      director --> measurements
      director --> drift
      director --> quantiles
      director --> variational
      variational --> viability

      state integrator <<join>>
      measurements --> integrator
      drift --> integrator
      quantiles --> integrator
      viability --> integrator
      integrator --> success
      
      daily --> failure
      structures --> failure

      success --> [*]
      failure --> [*]
```

<br>
<br>

<br>
<br>

<br>
<br>

<br>
<br>


<!--

<details><summary><b>Notes</b></summary>

<ul>
  <li>configurations: Records data & modelling configurations.</li>
  <li>iac: Infrastructure as code scripts.</li>
</ul>

</details>

-->

