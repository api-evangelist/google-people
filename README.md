# Google People API

The Google People API provides access to information about profiles and contacts. It enables reading and managing the authenticated user's contacts, contact groups, and profile information across Google services.

## APIs

- **Google People API** - Manage contacts, contact groups, and profile information.

## Base URL

```
https://people.googleapis.com/v1
```

## Key Endpoints

- **Get Person** - `GET /people/{resourceName}` - Get a person's profile or contact info
- **List Connections** - `GET /people/me/connections` - List the user's contacts
- **Search Contacts** - `GET /people:searchContacts` - Search contacts by query
- **Create Contact** - `POST /people:createContact` - Create a new contact
- **Update Contact** - `PATCH /people/{resourceName}:updateContact` - Update a contact
- **Delete Contact** - `DELETE /people/{resourceName}:deleteContact` - Delete a contact
- **List Contact Groups** - `GET /contactGroups` - List contact groups
- **Create Contact Group** - `POST /contactGroups` - Create a contact group

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/Person.json) - JSON Schema (draft 2020-12) for Person
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://developers.google.com/people/v1/getting-started)
- [API Reference](https://developers.google.com/people/api/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
