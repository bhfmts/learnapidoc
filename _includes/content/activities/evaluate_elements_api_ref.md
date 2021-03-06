## <i class="fa fa-user-circle"></i> Activity 3a: Evaluate API reference docs for core elements

In this activity, you'll review API reference documentation and identify the common elements. To evaluate the API reference docs:

1.  From this [list of about 100 API doc sites here](pubapis_apilist.html#list_api_doc_sites), identify three API documentation sites.
2.  In each of the doc sites, look for the API reference documentation section (the list of endpoints).
3.  In the reference documentation, identify each of the following sections:

    *  [Resource description](docapis_resource_descriptions.html)
    *  [Endpoints and methods](docapis_resource_endpoints.html)
    *  [Parameters](docapis_doc_parameters.html)
    *  [Request example](docapis_doc_sample_requests.html)
    *  [Response example and schema](docapis_doc_sample_responses_and_schema.html)

    (The section names may differ in the API doc sites you find, but they're usually recognizable.)

3.  Assess the API reference documentation by answering the following questions for each section:

    **Resource description:**
      *  Is the description action-oriented?
      *  Is it a brief 1-3 sentence summary?

    **Endpoints and methods:**
      *  How are the endpoints grouped? (Are they listed all on the same page, or on different pages? Are they grouped by method, or by resource?)
      *  How are the methods specified for each endpoint?

    **Parameters:**
      *  How many types of parameters are there (header, path, query string, and request body parameters) for the endpoints?
      *  Are the data types (string, boolean, etc.) defined for each parameter? Are max/min values noted?

    **Request example:**
      *  In what format or language is the request shown (e.g. curl, specific languages, other)?
      *  How many parameters does the sample request include?

    **Response example:**
      *  Is there both a sample response *and* a response schema? (And is each element in the response actually described?)
      *  How does the doc site handle nested hierarchies in the response definitions?

{% if page.workshop_activities == true %}*For more information related to this activity, see [Evaluate API reference docs for core elements](docapis_api_reference_activity.html).*{% endif %}
