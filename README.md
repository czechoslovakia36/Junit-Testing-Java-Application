# contact-manager-starter
Starter Project for the Junit 5 Tutorial


#Junit test lifecycle 
<ul>
<li>@BeforeAll</li>
<li>@BeforeEach</li>
<li>@Test</li>
<li>@AfterEach</li>
<li>@AfterAll</li>
</ul>

<hr>


<p>@BeforeAll,@BeforeEach -used to perform initialization tasks for tests</p>
<p>@AfterAll , @AfterEach - used to perform cleanup tasks for tests</p>


<hr>

<p><b>assertion:</b> means what is the expected value</p>

<p><b>assumption class:</b>failed assumptions do not result in a test failure; rather, a failed assumption results in a test being aborted.</p>


<h3>Parameterized tests</h2>
<ul>
<li>Test are executed with different set of input</li>
<li>substitutes @test</li>
<li>data is provided using different annotations</li>
@valueSource, @CsvSouce etc.
</ul>

<h1>nested tests</h1>
<ol>
<li>used to group tests together into a logical group</li>
<li>makes the test class more organized</li>
<li>@nested used to top of the class</li>
<li>can only use @BeforeEach and @AfterEach </li>
<li>Cannot use @BeforeAll and @AfterAll by default</li>
</ol>
