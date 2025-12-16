<style>
#program-table {
  text-align: left;
  padding: 0;
  border: none;
  margin: 20px auto;
  max-width: 100%;
  font-size: 0.95em;
  overflow: visible !important;
}

table tr {
  background-color: transparent !important;
}

#program-table > tbody > tr > td:first-child {
  font-weight: 600;
  white-space: nowrap;
  vertical-align: top;
  padding: 15px 20px;
  min-width: 100px;
  background-color: #f8f9fa;
  border-right: 2px solid #e8e8e8;
}

.session-table {
  padding: 0;
  border: none;
  margin: 10px 0 5px 0;
  width: 100%;
  overflow: visible !important;
}

.session-table tr {
  border-bottom: 1px solid #f0f0f0;
  border-top: none !important;
}

.session-table tr:last-child {
  border-bottom: none;
}

.session-table td {
  border: none !important;
  padding: 8px 12px;
  vertical-align: top;
}

.session-table td:first-child {
  font-weight: 500;
  color: #555;
  white-space: nowrap;
  min-width: 100px;
  padding-right: 15px;
}

.session-table td:last-child {
  padding-left: 0;
}

.poster-list {
  display: flex;
  flex-direction: column;
  padding-left: 15px;
}

.poster-list .poster-item {
  padding: 8px 0;
  border-bottom: 1px solid #f0f0f0;
}

.poster-list .poster-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.session-table p {
  margin-bottom: 4px;
  line-height: 1.5;
}

.session-table p:nth-child(1) {
  font-style: italic;
  pointer-events: none;
  color: #333;
  font-weight: 500;
}

/* Abstract tooltip styling */
.session-table p:nth-child(2) {
  position: relative;
  margin-left: 0;
  font-size: 0.9em;
}

.session-table .abstract-wrapper {
  position: relative;
  display: inline;
}

.session-table .abstract-link {
  font-style: normal;
  color: #999;
  font-size: 0.85em;
  text-decoration: underline;
  text-decoration-style: dotted;
  text-underline-offset: 2px;
  margin-left: 0.5em;
  cursor: help;
  display: inline;
}

.session-table .abstract-wrapper .abstract-content {
  display: none;
  position: fixed;
  background-color: #ffffff;
  border: 1px solid #ddd;
  border-radius: 4px;
  padding: 12px 14px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  z-index: 1000;
  width: auto;
  min-width: 240px;
  max-width: 520px;
  max-width: min(520px, calc(100vw - 32px));
  box-sizing: border-box;
  font-size: 0.9em;
  line-height: 1.5;
  text-align: left;
  white-space: normal;
  word-wrap: break-word;
}

@media screen and (max-width: 768px) {
  #program-table {
    font-size: 0.85em;
  }
  
  #program-table > tbody > tr > td:first-child {
    min-width: 100px;
    padding: 12px 15px;
    font-size: 0.9em;
  }
  
  #program-table > tbody > tr > td:last-child {
    padding: 12px 15px;
  }
  
  .session-table td:first-child {
    min-width: 80px;
    font-size: 0.9em;
  }
}

#program-table > tbody > tr > td:last-child p {
  margin-bottom: 8px;
}
</style>
<center>
<h1>2025 Midwest Programming Languages Summit</h1>
</center>

The 2025 Midwest Programming Languages Summit will take place on
<i>Saturday, December 13, 2025</i>, hosted by the [*Department of
Computer Science and Engineering*](https://cs.umn.edu)  at the
[*University of Minnesota, Twin Cities*](https://umn.edu).

The [*Midwest Programming Languages Summit*](https://mwpls.org) is an
informal workshop that is intended to foster the exchange of ideas and
to promote collaboration among faculty and students in the Greater
Midwest area. Anyone interested in programming languages and compilers
— including applications to areas such as systems, software
engineering, and human-computer interaction — is invited to
attend. Our aim is to have a broad selection of talks and posters
about ongoing research and any other topics that may be of interest to
the programming languages community. Student participation is
especially of interest; travel awards facilitated by a grant from the
National Science Foundation are available to encourage such
participation. The summit will have no formal proceedings, but
abstracts and slides will be distributed on the web after the
event.

This year's event is being organized by 
[Favonia](https://favonia.org/), 
[Gopalan Nadathur](https://cs.umn.edu/~ngopalan), and 
[Eric Van Wyk](https://cs.umn.edu/~evw)



# Dates

The important dates to keep in mind and deadlines to adhere to are the
following:


- **Friday, November 14, 2025:** Deadline for
  *[talk and poster proposals](https://forms.gle/wvwAzPzLdRsFEzKR7)*
  and to
  *[apply for travel grants](https://forms.gle/JrroCo1eexijSPJF8)*.
- **Wednesday, November 19, 2025:** Notification deadline for
talk/poster acceptance and grant awards
- **Monday, November 24, 2025:** Deadline to 
  *[register to attend](https://forms.gle/oKL5qQW4SiG2vaAA7)*.
- **Saturday, December 13, 2025:** Meeting date.

# Program  

The main venue for MWPLS 2025 is [Keller
Hall](https://campusmaps.umn.edu/kenneth-h-keller-hall) at the
University of Minnesota. Registration will take place in Room 3-176
Keller Hall and the talks will be held in Room 3-180 Keller Hall.
Lunch and the poster session will take place in the Beacon Room of the
[University Recreation and Wellness
Center](https://campusmaps.umn.edu/university-recreation-and-wellness-center),
which is about a block (or 5 minutes walking distance) east of Keller
Hall. Dinner will be an informal, buy-your-own affair, but we intend to organize a collective expedition to one of the local food and drinks halls (like [The Market at Malcolm Yards](https://malcolmyards.market/)). More details will be provided at the summit.

<table id="program-table">
  <tr>
    <td>8:00-9:00</td>
    <td>(3-176 Keller Hall) <b>Registration and breakfast</b></td>
  </tr>
  <tr>
    <td>9:00-9:10</td>
    <td>(3-180 Keller Hall) <b>Welcome and opening remarks</b></td>
  </tr>
  <tr>
    <td>9:10-9:20</td>
    <td>
      (3-180 Keller Hall) <b>Some words from our corporate sponsors</b> (AWS, Galois, SIFT)
    </td>
  </tr>
  <tr>
    <td>9:20-10:20</td>
    <td>
      (3-180 Keller Hall) <b>Session 1 of contributed talks</b> (Chair: Max New)
      <table class="session-table">
        <tr>
          <td>9:20-9:35</td>
          <td>
            <p>Structural Information Flow: A Fresh Look at Types for Non-interference</p>
            <p>
              Hemant Gouni, Frank Pfenning, Jonathan Aldrich
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                Information flow control is a long-studied approach for establishing <i>non-interference</i> properties of programs. For instance, it can be used to prove that a secret does not interfere with some computation, thereby establishing that the former does not leak through the latter. Despite their potential as a holy grail for security reasoning and their maturity within the literature, information flow type systems have seen limited adoption. In practice, information flow specifications tend to be excessively complex and can easily spiral out of control even for simple programs. Additionally, while non-interference is well-behaved in an idealized setting where information leakage never occurs, most practical programs <i>must</i> violate non-interference in order to fulfill their purpose. Useful information flow type systems in prior work must therefore contend with a definition of non-interference extended with <i>declassification</i>, which often offers weaker modular reasoning properties.<br><br>
                We introduce <i>structural information</i> flow, which both illuminates and addresses these issues from a logical viewpoint. In particular, we draw on established insights from the modal logic literature to argue that information flow reasoning arises from <i>hybrid logic</i>, rather than conventional modal logic as previously imagined. We show with a range of examples that structural information flow specifications are straightforward to write and easy to visually parse. Uniquely in the structural setting, we demonstrate that declassification emerges not as an aberration to non-interference, but as a <i>natural</i> and <i>unavoidable</i> consequence of sufficiently general machinery for information flow. This flavor of declassification features excellent local reasoning and enables our approach to account for real-world information flow needs without compromising its theoretical elegance. Finally, we establish non-interference via a logical relations approach, showing off its simplicity in the face of the expressive power captured.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>9:35-9:50</td>
          <td>
            <p>A Flow-Sensitive Refinement Type System for Verifying eBPF Programs</p>
            <p>
              Ameer Hamza, Lucas Zavalía, Arie Gurfinkel, Jorge A. Navas, Grigory Fedyukovich
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  The Extended Berkeley Packet Filter (eBPF) subsystem within an operating system's kernel enables userspace programs to extend kernel functionality dynamically. Because of the security risks arising from runtime modification of the OS, eBPF requires all programs to be verified before deploying them inside the kernel. Existing approaches to eBPF verification are monolithic, requiring their entire analysis to be done in a secure environment, resulting in the need for extensive trusted codebases. To reduce the size and complexity of the trusted codebase, we propose a type-based verification approach that automatically infers proof certificates in userspace, while only the proof-checking component needs to be deployed in a secure environment. Moreover, compared to previous techniques, our type system enhances the debuggability of the programs for users through ergonomic type annotations when verification fails. We implemented our type inference algorithm in a tool called VeRefine and evaluated it against an existing eBPF verifier, Prevail. VeRefine outperformed Prevail on most of the industrial benchmarks.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>9:50-10:05</td>
          <td>
            <p>Gradual Environment Classifiers</p>
            <p>
              Tianyu Chen, Darshal Shetty, Jeremy G. Siek, Chao-Hong Chen, Weixi Ma, Arnaud Venet, Rocky Liu
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Taha and Nielsen (2003) introduce environment classifiers (ECs) as a way to statically prevent scope extrusion in a metaprogramming language, that is, they prevent the generation of code that uses undefined variables. Our work adapts their notion of EC to a metaprogramming language with Gradual Typing (Siek and Taha, 2006), where one needs a dynamic mechanism for preventing scope extrusion in addition to the static one provided by Taha and Nielsen. Our key insight is to repurpose the generation and checking of runtime symbols that is used in gradual polymorphic languages (Ahmed et al. 2011). At runtime, we generate symbols that represent unique locations in the runtime environment. These symbols are called runtime environment classifiers. The EC variables in the program evaluate to runtime ECs, and because EC variables appear in types, runtime ECs appear in the type conversions that arise from gradual typing. So our work also introduces a runtime mechanism for checking conversions that involve runtime ECs based on the Coercion Calculus of Henglein (1994). Our current research is focused on proving the Type Safety theorem for our gradual metaprogramming language from which the absence of scope extrusion will be a corollary.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>10:05-10:20</td>
          <td>
            <p>Ground stratified induction for the logic of definitions</p>
            <p>
              Nathan Guermond, Gopalan Nadathur
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  The logic of definitions is a logic for reasoning about logical systems based on relational specifications. This logic extends first order intuitionistic logic with fixed-point definitions, which associate atomic predicates with formulas within which the predicate being defined may only occur strictly positively. Tiu has shown that this requirement can be relaxed to allow for negative occurrences of the predicate being defined via a condition known as ground stratification. In this framework, fixed-point definitions can be interpreted as least fixed-points by associating an induction rule with them. A question that naturally arises is whether the least fixed-point interpretation also extends to ground stratified definitions. In recent work we have shown that ground stratified definitions interpreted with the usual induction rule can lead to inconsistencies. In this work, we identify a generalization of the induction rule which is compatible with ground stratified definitions. This rule allows us to encode a strong normalizability proof for System T by Girard using an argument first introduced by Martin-Lof, in which reducibility is inductively defined by recursion on its arguments.
                </span>
              </span>
            </p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>10:20-10:50</td>
    <td><b>Break</b> (refreshments provided outside to 3-180 Keller Hall)</td>
  </tr>
  <tr>
    <td>10:50-11:50</td>
    <td>
      (3-180 Keller Hall) <b>Session 2 of contributed talks</b> (Chair: Jeremy Siek)
      <table class="session-table">
        <tr>
          <td>10:50-11:05</td>
          <td>
            <p>On the Relationship Between Environment Classifiers and Contextual Modal Types</p>
            <p>
              Tianyu Chen
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Metaprogramming is a paradigm where programs in a metalanguage generate code in an object language. It is nontrivial to guarantee the generation of well-typed and well-scoped object code, especially with the presence of mutable references in the metalanguage. Practical metaprogramming systems such as MetaOCaml (Kiselyov, Kameyama, Sudo 2016) have used the environment classifiers from MetaML (Taha and Nielsen 2003), which are markers in typing environments, to prevent scope extrusion, thereby guaranteeing that all generated code is type safe.<br><br>
                  Nanevski, Pfenning, and Pientka propose contextual modal type theory (CMTT), where the type system tracks both the type of the object code and the context in which the code is meaningful. In this talk, I present a compilation pass from a calculus with polymorphic environment classifiers, subtyping, and mutable references to a novel CMTT-based calculus that features contextual modal types and first-class substitutions. The key idea of this compilation is to identify the object language context that an environment classifier corresponds to.<br><br>
                  Our high-level research goal is to connect the line of work from MetaML/MetaOCaml with CMTT. We are especially curious about the expressiveness of environment classifiers compared to that of CMTT because object language bindings work fundamentally differently in the two systems. In a calculus with environment classifiers, an object language variable is bound by an object language λ-abstraction in its lexical scope; on the contrary, in CMTT an object variable is bound by the context annotation of the enclosing quote. Our compilation shows that CMTT is at least as expressive as environment classifiers. We also conjecture that the other direction of the compilation (that is, from CMTT to environment classifiers) is difficult because environment classifiers are more restrictive, identifying environments by name instead of by structure.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>11:05-11:20</td>
          <td>
            <p>Checking &delta;-Satisfiability of Reals with Integrals</p>
            <p>
              Cody Rivera, Bishnu Bhusal, Rohit Chadha, A. Prasad Sistla, Mahesh Viswanathan
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Many synthesis and verification problems can be reduced to determining the truth of formulas over the real numbers. These formulas often involve constraints with integrals in them. To this end, we extend the framework of δ-decision procedures with techniques for handling integrals of user-specified real functions. We implement this decision procedure in the tool ∫dReal, which is built on top of dReal. We evaluate ∫dReal on a suite of problems that include formulas verifying the fairness of algorithms, the privacy and the utility of privacy mechanisms, and formulas that synthesize parameters for the desired utility of privacy mechanisms. The performance of the tool in these experiments demonstrates the effectiveness of ∫dReal.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>11:20-11:35</td>
          <td>
            <p>A Relevance Sampler for μRustₛₗ</p>
            <p>
              Breandan Considine
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Programming languages increasingly rely on type systems to enforce disciplined use of resources such as memory, file handles and capabilities. Substructural logics, such as relevance logic, express obligations that every bound value must be used a certain number of times, but we currently lack generators that can produce realistic programs satisfying these constraints, limiting our ability to test, synthesize and repair such code in practice. In this talk, we will discuss a fixed-parameter tractable embedding of a relevant fragment of the Rust language into a family of context-free grammars (CFGs).<br><br>
                  Our key idea is to treat usage obligations as purely syntactic constraints: typing judgements in a substructural calculus (e.g., tracking which variables must, may, or must not be used) are compiled into a CFG whose nonterminals are annotated with sets of outstanding obligations and whose productions exactly mirror the underlying proof system. When intersected with a star-free regular expression and decoded in a pseudorandom order, this yields an exact sampler for relevant, affine or linear straight-line programs in the space of well-typed programs, parameterized by length and the number of tracked variables.<br><br>
                  Viewed through the lens of finite model theory, our construction realizes a bounded interpretation of substructural languages as context-free languages where each typing derivation corresponds to a finite language generated by our annotated grammar. This perspective makes the combinatorial structure of proof search explicit, clarifies which usage disciplines admit such embeddings, and isolates the parameters that govern the size and complexity of the resulting languages. In turn, it enables systematic stress-testing of compilers, synthesizers and program repair systems for resource-sensitive languages like Rust.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>11:35-11:50</td>
          <td>
            <p>Abella/Forum: A Framework for Reasoning about Linear Logic Specifications</p>
            <p>
              Terrance Gray, Thomas Tector, Gopalan Nadathur
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Linear logic is a useful formalism for encoding rule-based descriptions of object systems that embody resource usage. When formalized in this fashion, the task of reasoning about the properties of object systems reduces naturally to that of reasoning about linear logic specifications. We have adapted the Abella proof assistant towards providing such a capability. Abella embodies the "two levels of logic" approach in which a specification logic is embedded in a reasoning logic via a definition that captures its provability relation and actual specifications are reasoned about through this definition. In its original form, Abella uses a variant of intuitionistic logic as the specification logic. We have replaced that logic with Forum, which is a version of linear logic that has a computational interpretation. Reasoning about Forum specifications crucially requires the ability to analyze the derivability of Forum sequents. This ability is greatly aided by the fact that Forum is described by a focused proof system that has a goal-directed character. A complicating factor, however, is the fact that Forum derivations must consider partitioning multisets of assumption formulas that serve as linear resources. When the assumption formulas are known explicitly, a naive analysis of such partitioning has a combinatorial character. When the assumption formulas are identified only through a property, the explicit consideration of partitioning is not even an option. We solve both problems by utilizing a partition predicate, which is realized again via a definition in Abella, to provide a delayed treatment of partitioning. We obtain a logically concise treatment of these ideas through a representation of multisets that incorporates multiset union in the syntax and that treats such sets as invariant under permutations. This presentation will highlight these ideas and will illustrate their efficacy through specific reasoning examples.
                </span>
              </span>
            </p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>12:00-14:30</td>
    <td>
      (Beacon Room, Rec Center) <b>Lunch and Poster Session</b>
      <p>The following posters will be presented in the poster session:</p>
      <div class="session-table poster-list">
        <div class="poster-item">
          <p>Colobus: AoS to SoA transformation of recursive tree-like ADTs</p>
          <p>
            Vidush Singhal
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Algebraic data types are a language feature available in many functional programming languages like Haskell. They make it easier for programmers to define and work with complex data types. However, the performance of such programs depends on various factors, among which we are mainly interested in data layout.<br><br>
                  Gibbon is a compiler that supports a small language of tree traversals written in a subset of Haskell. It transforms programs that perform traversals on tree-like ADTs into corresponding traversals over the serialized representation of the ADT. This transformation enhances spatial locality, resulting in improved runtime performance.<br><br>
                  We take this data representation a step further by allowing such ADTs to be represented in either an array of structs (AoS) or a struct of arrays (SoA) serialization format. The structure-of-arrays layout can enable performance-critical optimizations such as vectorization over irregular, tree-like recursive data types, and it allows recursive traversals to be transformed into iterative loops.<br><br>
                  We build our tool on top of the Gibbon compiler, and for a subset of programs, the SoA transformation performs better due to improved locality. Preliminary results show that for certain reduction-like programs, we observe approximately a 2× speedup compared to baseline Gibbon.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Polygon: Symbolic Reasoning for SQL using Conflict-Driven Under-Approximation Search</p>
          <p>
            Pinhan Zhao
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  We present a novel symbolic reasoning engine for SQL which can efficiently generate an input I for n queries P₁, ..., Pₙ, such that their outputs on I satisfy a given property (expressed in SMT). This is useful in different contexts, such as disproving equivalence of two SQL queries and disambiguating a set of queries. Our first idea is to reason about an under-approximation of each Pᵢ -- that is, a subset of Pᵢ's input-output behaviors. While it makes our approach both semantics-aware and lightweight, this idea alone is incomplete (as a fixed under-approximation might miss some behaviors of interest). Therefore, our second idea is to perform search over an expressive family of under-approximations (which collectively cover all program behaviors of interest), thereby making our approach complete. We have implemented these ideas in a tool, Polygon, and evaluated it on over 30,000 benchmarks across two tasks (namely, SQL equivalence refutation and query disambiguation). Our evaluation results show that Polygon significantly outperforms all prior techniques.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Detecting Multi-Locale Anomalies in Chapel.</p>
          <p>
            Raneem Abu-Yosef, Thomas Huddleston, Kirshanthan Sundararajah, Martin Kong
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  The Partitioned Global Address Space (PGAS) execution model is a promising competing model to MPI. PGAS implementations offer several programmability advantages over their MPI counterparts while preserving the appeal of high-performance communication libraries. Among existing PGAS instances, the Chapel compiler and programming language is one of the most robust and well-supported implementations. Being around for nearly two decades, Chapel has evolved into a mature PGAS implementation, with several compiler and run-time features. As a result of these advances, several scientific libraries and applications have been written in Chapel. These include graph libraries, Finite Difference stencils, and Computational Fluid Dynamics (CFD), among many others. Unfortunately, despite these advances, the error detection support in Chapel has been largely ignored. In this work, we propose new static analyses to detect various distributed, multi-locale anomalies in Chapel programs. We leverage constraint formulae that model Chapel semantics together with anomaly-specific constraints that encapsulate triggering conditions of the anomaly. Generated models are then checked with Z3 SMT solver to decide the existence of anomalies. We demonstrate the effectiveness of our analyses on well-known scientific operators and communication patterns, comparing against native Chapel analyses and MPI debugging tools targeting lowered Chapel code.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Towards Improved Subgoal Synthesis for Induction in SMT</p>
          <p>
            Kartik Sabharwal, Andrew Reynolds, Cesare Tinelli
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  The SMT solver cvc5 hosts a suite of features for reasoning about functions defined over algebraic datatypes: quantifier instantiation procedures, finite model finding, structural induction, and syntax-directed enumerative subgoal synthesis. I will describe an approach to expand this suite with a conflict-directed subgoal synthesizer inspired by recent work in E-graph guided lemma discovery. The new conflict-directed synthesizer is intended to complement the heavy hammer of enumerative subgoal synthesis. It searches for a subgoal that conflicts with (refutes) a class of countermodels under consideration by the solver. The solver halts with a decision if and when all possible countermodels have been refuted. We have implemented our approach to conflict-directed synthesis in a new quantifiers module for cvc5. Our implementation currently performs better than syntax-directed enumerative subgoal synthesis on a suite of 311 benchmarks.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Towards Refinement Verification of Synchronous Programming with Automata</p>
          <p>
            Jiawei Chen, Serra Dane, Jean-Baptiste Jeannin
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Synchronous programming languages like Lustre and Esterel have a proven track record in industry for modeling complex cyber-physical systems (CPS) like avionics or industrial controllers. This is in part due to properties like the absence of deadlocks or causality which are easily checked statically or enforced by construction, which are also useful properties for real-world CPS to have. Additionally, the compilation and scheduling of synchronous programs has been extensively studied, making them reliably executable on real hardware.<br><br>
                  Verifying a synchronous programming language via the type system has been explored in existing work "Synchronous Programming with Refinement Types.", which presented a refinement type system for the synchronous programming language Zélus using a rewrite-based semantics. While the type system presented there is able to verify a subset of the synchronous kernel sufficient to control real-world hardware, its small-step semantic model does not fully support in a generalized way the equational semantics that underpin some core features of Zélus like hierarchical state machines and mutually recursive definitions. In general, the semantics is limited to only expressions that directly produce values, which is not the case for equational definitions in Zélus. Automata are an essential construct in Zélus for implementing more complex decision-making in discrete-time programs, and for the eventual implementation of hybrid automata which are a unique strength of Zélus's modeling and simulation capabilities. Similarly, generalized mutual recursion, while challenging for verification, allows one to write more expressive concurrent stream programs that more accurately model the interconnected components of a real system. To address this challenge, we introduce a state-based semantics and a new judgment system that can explicitly account for the evolving state of mutually recursive definitions and automata across time. This lets us extend refinement-based verification beyond simple expression-level kernels to the richer equational and automaton constructs that are needed to model realistic CPS controllers in Zélus.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Automatic Certification of the Active Corner Method for Collision Avoidance</p>
          <p>
            Nishant Kheterpal
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Formal methods are particularly useful to guarantee safety before deployment in safety-critical tasks. Ensuring absence of collision for vehicles such as airplanes, cars, or robots is one common application of formal verification. However, many methods for verifying collision avoidance model a vehicle as a moving point mass, though the real vehicles have non-zero area. Our past work proposed a novel algorithm (the active corner method) for verifying collision avoidance for polygonal objects moving in the plane, along with a Python implementation. That implementation was not verified or certified, relying instead on a pen-and-paper proof of correctness. In this work, we describe an extension of the active corner method to automatically generate machine-checkable proof certificates of correctness for specific instances within the Prototype Verification System (PVS). This work briefly discusses the original active corner method proof approach, presents a novel algebraic approach that generalizes to any convex polygon, details the certification process with examples in PVS, and provides a case study using the differential dynamic logic integration within PVS.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Dependent-types for Python Libraries for Shape Analysis</p>
          <p>
            Arnav Jain and Sankha Guria
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Tensor libraries like NumPy are essential tools for programmers, enabling the efficient representation and manipulation of massive datasets. Although NumPy streamlines array processing, it abstracts away the implementation details of tensor operations, leaving the user responsible for ensuring that tensor shapes are compatible. This dependency on shape compatibility makes NumPy code highly susceptible to run-time errors that standard type checkers, such as MyPy or PyRight, are unable to detect because they are shape-unaware. In this work, we introduce a novel dependent type system for tensor operations, designed to detect shape errors statically. The key design decision in our system is to use dependent types to check application code but not verify the NumPy implementation itself. This allows us to write expressive type signatures that can do symbolic manipulation to verify arbitrary tensor shapes. We implement our system as MyPy plugin, giving it access to type check the entire Python ecosystem. We evaluate our system on an open-source machine learning project that relies on NumPy operations, including broadcasting, matrix multiplication, reshape, and slicing, demonstrating its effectiveness in a real-world context. In summary, we believe this shape-aware type system represents an important step forward in ensuring the robustness and correctness of code using tensor libraries like NumPy.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Group Cohomology in Cubical Agda</p>
          <p>
            Kelton OBrien
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Homotopy type theory is an extension of dependent type theory that allows the interpretation of types as spaces, elements of types as points in that space, and equalities as paths. This made synthetic mechanizations of algebraic topology and related subjects such as homological algebra possible for the first time. Group cohomology is a foundational concept in the field of homological algebra, but this notion has not been mechanized in a homotopy type theory based proof assistant, preventing the computer verification of large swathes of homological algebra. We provide a mechanization of the first cellular model of the delooping of any finite group in Cubical Agda. We use this cellular delooping to formalize the notion of the cohomology groups of a finite group, and allow for their computation in a proof assistant for the first time, as well as synthetically mechanizing several important lemmas in algebraic topology in a proof assistant for the first time.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Biscotti: An Approach to Parallel Scheduling for Vectorized Encrypted Arithmetic Circuits</p>
          <p>
            Vedant Paranjape, Aman Gupta, Sreevickrant Sreekanth, Dulani Wijayarathne, Raghav Malik, Milind Kulkarni
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Fully Homomorphic Encryption (FHE) enables secure computation on encrypted data, ensuring privacy in various applications. However, FHE's practicality is constrained by the substantial overhead of encrypted computation. This overhead can be partially mitigated by using vectorization strategies to optimize FHE computations. The unique semantics of FHE computations make vectorizing arbitrary applications challenging, so recent research (e.g. Coyote [1] and Porcupine [2]) focuses on applying synthesis-based techniques, which have the drawback of failing to scale well to vectorizing large programs. We propose Biscotti, an FHE vectorizer that targets "divide-and-conquer" parallelism in recursive programs. Biscotti identifies smaller subproblems that can be vectorized independently using off-the-shelf synthesis based approaches, and then uses a novel algorithm to combine these into a vector schedule for the full program. We demonstrate on a variety of common benchmarks that Biscotti's approach not only improves compilation times, but also results in more efficient schedules overall.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Ariadne: Discovering PBT Generator Weights with Dynamic Sampling</p>
          <p>
            Francille Zhuang
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Property Based Testing (PBT) is a popular automated testing methodology that uses thousands of randomly generated inputs to probe a program's behavior. PBT frameworks create these inputs using input generators, functions that non-deterministically sample from the input space of the program under test. To be effective, input generators must produce representative samples of the inputs of interest. However, manually adjusting the distribution of a generator is a tedious and error prone task.<br><br>
                  This work introduces a technique for automatically tuning an input generator to better align with a specified target distribution. The proposed technique stochastically modifies the generator, by using dynamic sampling to estimate how closely its outputs align with the target distribution. Compared to prior work, our proposed approach supports richer classes of target distributions and input generators. As one example, our approach can automatically tune a red black search tree generator to produce trees with uniformly distributed heights. In addition, our approach can ensure that a generator produces values that satisfy a disjoint set of predicates. We have realized our technique in a tool called Ariadne; our experiments show that Ariadne can automatically adjust generators for a diverse set of data types so that they produce samples that align with a variety of semantically rich target distributions.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Compiling Structured Operational Semantics to Executable OCaml Code</p>
          <p>
            Linglong Meng
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  Structured Operational Semantics (SOS) translates naturally to logic programming languages like Prolog, which support backtracking, nondeterministic rule selection and unification. Functional languages like OCaml, however, require deterministic pattern matching, making direct SOS translation challenging. We demonstrate our approach with an imperative language (IMP) featuring arithmetic and boolean expressions, variable assignment, control flow, and loops. The same SOS specification generates both executable Prolog and OCaml implementations, showing that carefully designed semantics can target both logic and functional paradigms.
              </span>
            </span>
          </p>
        </div>
        <div class="poster-item">
          <p>Encoding Occurrence Typing in Rocq</p>
          <p>
            Sujin Woo and Sam Tobin-Hochstadt
            <span class="abstract-wrapper">
              <span class="abstract-link">(Abstract)</span>
              <span class="abstract-content">
                  We present an embedding of Typed Racket in Rocq, demonstrating that occurrence typing can be directly encoded using full-spectrum dependent types. Occurrence typing uses propositions based on the evaluation of a predicate to narrow the type of a given variable. Central to our encoding are Rocq's subset types and Program tactic, which allow us to pass derived propositions carrying type information alongside variables to model occurrence typing. To make our embedded programs resemble Typed Racket programs, we define notations to bring the syntax of the language closer to Typed Racket, and tactics automate away trivial obligations produced by definitions. We show that our embedding can express examples of occurrence typing in the literature, including Guo and Greenman's recent if-T benchmark programs.
              </span>
            </span>
          </p>
        </div>
      </div>
    </td>
  </tr>
  <tr>
    <td>14:50-16:05</td>
    <td>
      (3-180 Keller Hall): <b>Session 3 of contributed talks</b> (Chair: Garrett Morris)
      <table class="session-table">
        <tr>
          <td>14:50-15:05</td>
          <td>
            <p>Virtualizing Continuations</p>
            <p>
              Cong Ma
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Effect handlers and multishot continuations are powerful abstractions for managing control flow; together, they offer concise and modular ways to express and handle nondeterminism, randomness, and more. However, implementing multishot continuations in the presence of stack-allocated lexical resources—lexical effect handlers in particular—is challenging, since stack copying invalidates references to these resources.<br><br>
                  In this talk, I will present a novel implementation strategy for lexical effect handlers that fully supports multishot continuations. The key idea is to virtualize the stack space used by continuations. Each stack-allocated handler instance is assigned a virtual address, and all effect invocations through these virtual addresses are mediated by an address translation mechanism. A software-based memory management unit in the runtime system performs these translations efficiently, exploiting the lexical scoping discipline of effect handlers.<br><br>
                  We capture the essence of our approach via a new operational semantics for lexical effect handlers and prove it correct with respect to the standard semantics. We also implement it in a compiler and runtime system. Compared to prior languages with lexical effect handlers, our implementation increases expressivity by fully supporting multishot continuations—and, as a happy consequence, unlocks significant performance gains by enabling parallel execution of multishot continuations.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>15:05-15:20</td>
          <td>
            <p>System FD: Towards making ad-hoc polymorphism even less ad-hoc</p>
            <p>
              Apoorv Ingle
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  GHC/Haskell language extensions provide features like type classes and type families to make the language expressive and enable programmers to express type correct extensible code. In this talk I will focus on functional dependencies, a type class extension which has been used to aid type inference. However, this superficial treatment of functional dependencies causes usability issues. I will then discuss System FD, a novel core language, that naturally expresses functional dependencies in the language which can be used to resolve the tension between functional dependencies and type families.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>15:20-15:35</td>
          <td>
            <p>Code Style Sheets</p>
            <p>
              Sam Cohen and Ravi Chugh
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Program text is rendered using impoverished typographic styles. Beyond choice of fonts and syntax-highlighting colors, code editors and related tools utilize very few text decorations. These limited styles are, furthermore, applied in monolithic fashion, regardless of the programs and tasks at hand.<br><br>
                  We present the notion of code style sheets for styling program text. Motivated by analogy to cascading style sheets (CSS) for styling HTML documents, code style sheets provide mechanisms for defining rules to select elements from an abstract syntax tree (AST) in order to style their corresponding visual representation. Technically, our selector language generalizes essential constructs from CSS to a programming-language setting with algebraic data types (such as ASTs). Practically, code style sheets allow ASTs to be styled granularly, based on semantic information—such as the structure of abstract syntax, static type information, and corresponding run-time values—as well as design choices on the part of authors and readers of a program.<br><br>
                  In addition to these technical and practical aspects, my talk will discuss our efforts to integrate code style sheets into a code editor, and how style sheets might be extended to affect a program's text layout as well as its visual style.<br><br>
                  This talk includes work originally presented at UIST 2025 and OOPSLA 2025.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>15:35-15:50</td>
          <td>
            <p>A Marriage of Scope Graphs and Reference Attribute Grammars</p>
            <p>
              Luke Bessant
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Scoping structure and behavior are integral parts of a programming language definition that have been widely implemented using ad-hoc, language-specific approaches, hampering their re-usability and making reasoning about them more difficult. With the goal of defining a universally applicable name binding framework, the scope graphs model was introduced by Eelco Visser et al., including a theory of scopes and declarations encoded as graphs, as well as a generic name resolution algorithm for querying these structures.<br><br>
                  This theory was previously only applied in constraint-solving systems, but our recent work has shown what was common folklore in the attribute grammars community, scope graphs have a natural home in demand-driven reference attribute grammars. Reference attributes define references between the nodes in a program's abstract tree, or from the tree to nodes that extend it at compile time, and are a convenient way to represent edges in a scope graph. Demand-driven evaluation of attribute grammars provides a model for interleaving the construction and interrogation of scope graphs, supporting language features such as type-dependent name resolution. We have also used circular reference attribute grammars to support notions of self-influencing, circularly defined name resolution. In this talk/poster we describe the representation of scope graphs in reference attribute grammars and present an implementation of a generic library for defining scope graphs for programming languages.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>15:50-16:05</td>
          <td>
            <p>Flexible Efficient Memory Management and Compile-Time Specialization via Context</p>
            <p>
              Sam Estep and Joshua Sunshine
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  Efficient systems programming depends on the language to provide tools to manage memory (e.g. via malloc/free, RAII, smart pointers, and/or borrow checking), as well as tools to compile away abstractions into specialized code (e.g. via macros, templates, generics, traits, and/or compile-time execution). However, mainstream systems languages like C, C++, and Rust make it overly difficult to use strategies other than the relatively inefficient system allocator, leading newer systems languages to either require allocation to be made more explicit (e.g. Zig), or make allocation implicit via a special context struct that gets passed to every function (e.g. Odin). This work instead takes inspiration from work on coeffects, proposing an alternative solution that is more ergonomic and more general: declarations of values, functions, and types are decoupled from their binding sites, which can be either static (to improve runtime performance) or dynamic (to reduce binary size). By allowing not only values but also types to be contextual, this unified treatment of context facilitates more efficient systems programming with less engineering effort.
                </span>
              </span>
            </p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>16:05-16:35</td>
    <td><b>Break</b> (refreshments provided outside to 3-180 Keller Hall)</td>
  </tr>
  <tr>
    <td>16:35-17:35</td>
    <td>
      (3-180 Keller Hall): <b>Session 4 of contributed talks</b> (Chair: Jean-Baptiste Jeannin)
      <table class="session-table">
        <tr>
          <td>16:35-16:50</td>
          <td>
            <p>Quantum Assertion Testing Without Mid-Circuit Measurement: Strategies and Lower Bounds</p>
            <p>
              Shengyuan Yang and Charles Yuan
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  To make quantum computing more practical and ubiquitous, we must develop more general and robust ways to detect bugs in quantum programs. Prior work on runtime quantum assertions has focused on the expressiveness of individual assertions and their construction as quantum circuits, but a complementary question—how to effectively check multiple assertions in a quantum program—has been less explored.<br><br>
                  In this work, we study the time–space trade-offs for testing quantum assertions in a practical hardware setting without mid-circuit measurement. We define a family of target problems by formalizing the possible levels of learnable information about a quantum program that uses multiple assertions, including deciding whether any assertion fails (ExistFail) or outputting the index of the first failing assertion (FirstFail). For each of these problems, we establish a time–space trade-off lower bound, where "time" is the number of program runs and "space" is the number of ancilla qubits used per run. We also give matching strategies, which implies each lower bound we establish is tight.<br><br>
                  For most of these problems, our strategies asymptotically improve over the time–space trade-off achieved by the two naïve baselines (either using one run with n ancillas, or using n runs with a single ancilla). Moreover, it also shows that mid-circuit measurement does not yield a decisive O(n) advantage over strategies not relying on mid-circuit measurements.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>16:50-17:05</td>
          <td>
            <p>Safety Verification of Anytime Perception based Cyber-Physical Systems</p>
            <p>
              Lipsy Gupta and Pavithra Prabhakar
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  AI-based components are increasingly integrated into autonomous and cyber-physical systems (CPS) by replacing traditional modules such as control, perception, and decision-making. These integrations have led to significant advancements in safety-critical domains, including aerospace, automotive, and robotics. The paradigm of anytime perception has been recently introduced to offer flexibility in latency and accuracy, unlike traditional sensors that return outputs with fixed performance. On one hand, this adaptability enables autonomous systems to perform more complex tasks while ensuring efficient use of computational resources. On the other hand, it introduces new safety challenges, as variations in sensing performance can lead to mission-critical failures. To address these challenges, formal verification is emerging as a powerful framework for providing guarantees on the correctness and safety of such systems.<br><br>
                  In this talk, we focus on the safety verification of anytime perception-based CPS, wherein we model the anytime sensor in the closed loop. We provide an efficient algorithm for reachable set computation of a closed-loop system with an anytime sensor and a neural network controller using the star set data structure and designing new algorithms for some star set operations.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>17:05-17:20</td>
          <td>
            <p>Fluorite: A Calculus for SQL Queries With Ordering</p>
            <p>
              Jesse C. Slater, Xinyu Wang, Ryan Marcus, Max S. New
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  A prerequisite to SQL compiler verification is a formal semantic foundation for SQL. Formalizations of SQL have traditionally relied on unordered semantics for tables based on sets or multi-sets, but SQL contains important operations such as LIMIT and ORDER BY which cannot be formalized with unordered table semantics. We present Fluorite, a simple calculus which serves as a semantic foundation for SQL queries with ordering. Fluorite uses a nondeterministic semantics over lists to support both ordered and unordered operations. It includes an equational theory which can be used to prove interesting query equivalences. We implement Fluorite's semantics and verify its equational theory in the Lean proof assistant.
                </span>
              </span>
            </p>
          </td>
        </tr>
        <tr>
          <td>17:20-17:35</td>
          <td>
            <p>Learning Short Clauses via Conditional Autarkies</p>
            <p>
              Amar Shah, Twain Byrnes, Joseph Reeves, Marijn Heule
              <span class="abstract-wrapper">
                <span class="abstract-link">(Abstract)</span>
                <span class="abstract-content">
                  State-of-the-art Boolean satisfiability (SAT) solvers increasingly use techniques beyond resolution. One of the strongest such techniques is Propagation Redundant (PR) clause learning. Solvers utilizing PR clause learning may admit short proofs for benchmark families with exponentially large resolution proofs, including pigeonhole and mutilated chessboard. However, existing PR clause learning techniques require an NP-hard check; hence, they are computationally expensive and difficult to add to existing tools.<br><br>
                  We propose a new technique for learning PR clauses based on conditional autarkies and implement it in the SAT solver Cadical. Our method is modular, allowing for cross-solver compatibility, and learns PR clauses in linear time. Additionally, we introduce a number of heuristics, including a clause-shrinking technique and filtering to avoid trivial PR clauses, ensuring that our method learns useful clauses. We show that this is competitive with state-of-the-art PR clause learning techniques, and improves performance on a portion of SAT competition benchmarks.<br><br>
                  This work appeared at FMCAD 2025.
                </span>
              </span>
            </p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>17:35-17:45</td>
    <td><b>Closing remarks</b></td>
  </tr>
  <tr>
    <td>18:00-20:30</td>
    <td><b>Dinner</b></td>
  </tr>
</table>

# Event Details

## Venue

As previously indicated, the main venue for the summit is [Keller
Hall](https://campusmaps.umn.edu/kenneth-h-keller-hall), the home of
the Computer Science and Engineering Department on the east bank of the
Minneapolis campus of the University of Minnesota. Once you have arrived here, we will acquaint you with the other places that are relevant to what will happen during the day.

<center>
<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1SD-pEHoj8tcwQb_7fbRYS6no-FEsTHk&ehbc=2E312F"
width="640" height="480"></iframe>
</center>

## Accommodation

The nearest hotel, which is only one block from Keller Hall is the [Graduate by Hilton
Hotel](https://www.hilton.com/en/hotels/mspgmgu-graduate-minneapolis/). Other
options that are all within walking distance include the [Days Hotel by
Winham](https://www.wyndhamhotels.com/days-inn/minneapolis-minnesota/days-inn-hotel-university-ave-se/overview?CID=LC:DI:20160927:RIO:Local:SM-diwnct)
on University Avenue, the [Hilton Garden
Inn](https://www.hilton.com/en/hotels/msputgi-hilton-garden-inn-minneapolis-university-area/),
and, just across the Mississippi river, the [Courtyard by
Marriott](https://www.marriott.com/en-us/hotels/mspdc-courtyard-minneapolis-downtown/overview/).

When considering other options, such as through Airbnb, it would be
prudent to check access by [public
transit](https://www.metrotransit.org/home) to the campus. The [Metro
Transit Green Line](https://www.metrotransit.org/route/green), for
example, has a stop right outside Keller Hall and it runs from
downtown Minneapolis (just a few stops away) all the way to downtown St. Paul
(many stops further away).

We could unfortunately not work out special rates for hotels; we could get these only if blocked a set of rooms and guaranteed occupancy, a commitment that the summit budget did not allow us to make. You may ask the organizers if you have questions about other accommodations, such as about the suitability of the location of a place you may have identified using Airbnb. 


## Travel / Public Transit

### By air

One can fly to the [Minneapolis St. Paul International
Airport](https://www.mspairport.com/), code **MSP**.
From the airport, take the 
[Blue Line](https://www.metrotransit.org/route/blue) 
towards Minneapolis to the US Bank Stadium stop. From here, catch the
[Green Line](https://www.metrotransit.org/route/green)
towards St. Paul and get off at the East Bank stop. This is right in
front of Keller Hall where the workshop is taking place.

### By rail

Amtrak has a two connections between Minneapolis and Chicago that
makes for a pleasant journey arriving at the 
[Union Depot](https://www.uniondepot.org/) in St. Paul. The best
option may be the [Borealis](https://www.amtrak.com/borealis-train), a
dedicated line between Chicago and Minneapolis. The [Empire
Builder](https://www.amtrak.com/empire-builder-train), which goes via
St. Paul/Minneapolis from Chicago to Seattle and vice versa, is
another possibility. From the train station / Union Depot, take the
[Green Line](https://www.metrotransit.org/route/green)
towards Minneapolis and get off at the East Bank stop.


## Parking

Parking on the University of Minnesota East Bank campus is,
unfortunately, not the easiest of propositions. The best option for
day parking is to use University of Minnesota parking
ramps. Information on these facilities can be found in the
**University Parking** section of the [Keller
Hall](https://campusmaps.umn.edu/kenneth-h-keller-hall) web page. 

## Travel Grant Reimbursements

If you received a Travel Grant to cover part of your expenses then you
should follow these **NEW** instructions for receiving your reimbursement.

1. Collect that (digital) receipts for which you expect to be
   reimbursed. We recommend submitting these for more than the amount
   of your travel grant (assuming the travel grant does not cover all
   of your expenses) in case there are extra funds that can be
   distributed. 

2. Use [this Google Form](https://docs.google.com/forms/d/1uPCUPg9fOkJZII2SV4K6IHUmXKmGNifAXvPhE8RPpfQ/viewform?ts=627a8b15&edit_requested=true)
   to initiate the reimbursement process.
   
   On the form, indicate that the reimbursement is for "travel related
   to academics or research".
   
   Attach your receipts and also a PDF of the email you received
   that notified you of your travel grants and its amount.


   For the approved shortcode at the end of the form, use 013389.
   
3. This must be completed by **January 9, 2026**.



# Sponsors

The event is being supported by the [National Science
Foundation](https://nsf.gov), the [Department of Computer Science at
the University of Minnesota](https://cs.umn.edu), the automated
reasoning group in Minneapolis ([an internship program in automated
reasoning](https://amazon.jobs/en/jobs/3050073/2026-applied-science-internship-automated-reasoning-united-states-phd-student-science-recruiting))
of *Amazon Web Services*, the [Galois](https://galois.com) group in
Minneapolis and [SIFT: Smart Information Flow
  Technologies](https://sift.net). 


<table>
<tr>
<a href="https://nsf.gov"><img src="NSF.png" height="150" width="150"></a>
<img src="spacer.png" height="150" width="10">
<a href="https://cs.umn.edu"><img src="cse.png"
  height="100" width="813"></a>
  </tr>
<tr>
  <a
  href="https://amazon.jobs/en/jobs/3050073/2026-applied-science-internship-automated-reasoning-united-states-phd-student-science-recruiting"><img
  src="aws.png" height="150" width="293"></a>
  <img src="spacer.png" height="150" width="30">
  <a href="https://galois.com"><img src="galois.png" height="150" width="572"></a>
</tr>
<tr>
  <a href="https://sift.net"><img src="sift.png" height="150"></a>
  </tr>
</table>

<!-- code to position abstracts -->
<script>(()=>{const t=16,e=(t,e,n)=>n<e?e:Math.min(Math.max(t,e),n);let n=null;const i=(n,i)=>{const{clientWidth:o,clientHeight:l}=document.documentElement,s=n.getBoundingClientRect(),a=Math.max(160,o-32),c=Math.min(520,a),d=Math.min(240,c);let r=c;Object.assign(i.style,{position:"fixed",display:"block",visibility:"hidden",width:`${r}px`,maxWidth:`${c}px`,minWidth:`${d}px`,maxHeight:"",overflowY:"",left:"16px",top:"16px",right:"",bottom:""});let h=i.getBoundingClientRect().height,m=e(s.left+s.width/2-r/2,t,o-t-r);const p=o-t-m;r>p&&(r=Math.max(d,p),i.style.width=`${r}px`,h=i.getBoundingClientRect().height,m=e(s.left+s.width/2-r/2,t,o-t-r));const u=l-(s.bottom+10)-t,b=s.top-10-t,g=h<=u||!(h<=b)&&u>=b?"below":"above";let y="below"===g?u:b;h>y&&(y=Math.max(100,y),i.style.maxHeight=`${y}px`,i.style.overflowY="auto",h=i.getBoundingClientRect().height);const v=e("below"===g?s.bottom+10:s.top-10-h,t,l-t-h);Object.assign(i.style,{left:`${m}px`,top:`${v}px`,visibility:"visible"})},o=t=>{t&&(Object.assign(t.style,{display:"none",visibility:"",width:"",maxWidth:"",minWidth:"",left:"",top:"",maxHeight:"",overflowY:""}),n===t&&(n=null))};document.addEventListener("DOMContentLoaded",(()=>{const t=[];let e;Array.from(document.querySelectorAll(".session-table .abstract-link")).forEach((e=>{const l=e.closest(".abstract-wrapper")?.querySelector(".abstract-content");if(!l)return;let s;t.push({link:e,content:l});const a=()=>{s&&(clearTimeout(s),s=null),i(e,l)},c=()=>{s=setTimeout((()=>o(l)),40)};e.addEventListener("mouseenter",a),l.addEventListener("mouseenter",a),e.addEventListener("mouseleave",c),l.addEventListener("mouseleave",c),e.addEventListener("pointerdown",(t=>{"touch"===t.pointerType&&(t.preventDefault(),t.stopPropagation(),clearTimeout(s),s=null,n&&n!==l&&o(n),"block"===l.style.display?o(l):(i(e,l),n=l))}))})),document.addEventListener("pointerdown",(t=>{if("touch"!==t.pointerType)return;const e=t.target;e.closest(".abstract-wrapper")||e.closest(".abstract-content")||o(n)})),window.addEventListener("resize",(()=>{clearTimeout(e),e=setTimeout((()=>{t.forEach((({link:t,content:e})=>{"block"===e.style.display&&i(t,e)}))}),100)}))}))})();
</script>
