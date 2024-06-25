# Replicate WhereIsCaliforniaOnFire

## Objective

The goal of this coding exercise is to replicate the functionality of Where is
California on Fire using Django 4.2 and data from the California Fire Incidents
API.  Additonally we prefer engineering rigor over speed for this exercise.

### Setup Instructions

1. Clone the Repository

The initial codebase for this exercise is hosted on GitHub. Please follow the
steps below to clone the repository into Repl.it:

    - Go to [Repl.it](https://repl.it/).
    - Create an account or log in if you already have one.
    - Click on the “Import from GitHub” button.
    - Enter the URL of the GitHub repository:  `https://github.com/NationalServicesGroup/django-replit-template.git`
    - Click on “Import from GitHub”.
    - Follow the rest of the instructions in the top level `README.md`

### Exercise Requirements

Your task is to replicate the functionality of [Where is California on Fire](http://whereiscaliforniaonfire.com/) using the data 
from the [California Fire Incidents API](https://incidents.fire.ca.gov/umbraco/api/IncidentApi/List?inactive=false).
Specifically, you need to:


1. **Fetch Data**

Use the API endpoint
`https://incidents.fire.ca.gov/umbraco/api/IncidentApi/List?inactive=true` to
fetch the list of fire incidents. You can use Django's built-in tools or any
third-party libraries to make HTTP requests.

2. **Data Display**

Create views and templates to display the fire incident data. The main page
should show a list of all active fire incidents, including their key details.

3. **Data Modeling**

Create a model via the ORM to log each time the page is viewed.  Have a separate
page to view the page views. Paginate if time permits.


#### Resources

- [Django Documentation](https://docs.djangoproject.com/en/4.2/)
- [Repl.it Documentation](https://docs.replit.com/)
- [California Fire Incidents API](https://incidents.fire.ca.gov/umbraco/api/IncidentApi/List?inactive=false)
