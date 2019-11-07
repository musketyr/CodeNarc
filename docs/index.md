---
layout: default
title: CodeNarc
---  

# CodeNarc

## Static Analysis for Groovy

**CodeNarc** analyzes Groovy code for defects, bad practices, inconsistencies, style issues
and more. A flexible framework for rules, rulesets and custom rules means it's easy to configure CodeNarc
to fit into your project. Build tool, framework support, and report generation are all enterprise ready.

<table>
<tr>
    <td width="50%">
         <div class="section">
              <h2>CodeNarc Rules"</h2>
              CodeNarc triggers violations based on rules. Click the links to the left to view the
              <a href="codenarc-rule-index.html">index of all rules</a>, or individual rule categories (rulesets), such as
              the <a href="codenarc-rules-basic.html">basic</a>, or <a href="codenarc-rules-concurrency.html">concurrency</a>
              rules. Or you can <a href="codenarc-creating-ruleset.html">create your own ruleset</a>;
              see how easy it is in this <a href="http://www.youtube.com/watch?v=ZPu8FaZZwRw">screencast</a>.
         </div>
     </td>
    <td valign="middle" align="middle" style="margin:auto; vertical-align:middle">
        <div>
            <a style="color:white;font-size:20pt;font-weight:bold; margin:auto; border:solid white; border-radius:25px; background-color:red; padding:20pt;"
               href="http://sourceforge.net/projects/codenarc/files//">Get 1.5</a>
        </div>
    </td>
</tr>
<tr>
     <td>
          <section name="Running CodeNarc">
                 Run CodeNarc with the <a href="codenarc-ant-task.html">Ant Task</a>,
                 the <a href="codenarc-command-line.html">command-line runner</a>, or
                 <a href="codenarc-run-as-a-test.html">as part of your test suite</a>.
                    Also,  plugins exist for <a href="codenarc-other-tools-frameworks.html">Maven</a>,
                   <a href="codenarc-other-tools-frameworks.html">Gradle</a>, <a href="codenarc-other-tools-frameworks.html">Grails</a>,
                   <a href="codenarc-other-tools-frameworks.html">Griffon</a>,
                   <a href="codenarc-other-tools-frameworks.html">SonarQube</a>
                   and <a href="codenarc-other-tools-frameworks.html">Jenkins</a>. See our
                    <a href="codenarc-other-tools-frameworks.html">Integration</a> page for more details.
               Reports come in HTML, XML, or text format.  Take a look at a
               <a href="SampleCodeNarcHtmlReport.html">Sample CodeNarc HTML Report</a>,
               or a <a href="./SampleCodeNarcXmlReport.xml">Sample CodeNarc XML Report</a>.
          </section>
     </td>
     <td>
     <section name="Requirements">
          <strong>CodeNarc</strong> requires:
          <ul>
              <li>Java 1.6 or later</li>
              <li><a href="http://groovy-lang.org/">Groovy</a> version 2.3 or later</li>
              <li><a href="https://www.slf4j.org/">SLF4J</a> API and binding jar(s)</li>
              <li><a href="https://dx42.github.io/gmetrics/">GMetrics</a> 1.0 or later, if using the Size/Complexity rules</li>
          </ul>
     </section>
     </td>
</tr>
<tr>
     <td>
          <section name="Get it from Maven2">
               For projects built using <a href="http://maven.apache.org/">Maven</a>, <strong>CodeNarc</strong> is available
               from the
                   <a href="http://repo1.maven.org/maven2/org/codenarc/CodeNarc/">Maven Central Repository</a>
                    <ul>
                         <li>groupId = org.codenarc</li>
                         <li>artifactId = CodeNarc</li>
                    </ul>
          </section>
     </td>
     <td>
          <section name="Inspirations">
             We're inspired by the wonderful <a href="http://pmd.sourceforge.net/">PMD</a>
            and <a href="http://checkstyle.sourceforge.net/">Checkstyle</a> Java static analysis tools, as well
            as the extensive Groovy inspections performed by <a href="http://www.jetbrains.com/idea/">IntelliJ IDEA</a>.
          </section>
     </td>
</tr>
</table>