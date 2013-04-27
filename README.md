technedict
----------

A dictionary for any technical field that breaks the bounds of language.

This project comes in two parts. The first is the simple SPEC that can be implemented in any setting you choose. Also included are example implementations using Flask. 

See Specification.

See Flask App -- Website

See Flask App -- API

**Current Status: v.0.1 α1 -- For Review, UNSAFE**

## Base URL Methods

Calling in the Browser (Client Facing Webpage) should be similary designed as the API methods. The only difference will be that the calls to API will be made to `http://api.pdo.com/w/...` rather than `http://pdo.com/w/...`.

HTTP methods are important to make correctly, because this will *not* be the same language in all places, and it's important to make sure everything renders correctly and is semantically engaged.

API will return one of these four types:

- **HTML (Non-rendered)**
- **HTML (Rendered)**
- **JSON**
- **XML**

All these are given as UTF-8.

## Basics (Browser Calling)

  /w/
	/w/{query}
	/w/{query}/{lan}

### Localization

	/w/{lan}/{query}/
	/w/{lan}/{query}/{lan}

### A Note on the Language Thing

## Parts (API Calling)

	/w/{query}
	/w/{query}/{definition}/{id}
	/w/{query}/{example}/{id}
	/w/{query}/{pronunciation}
	/w/{query}/{etemology}
	/w/{query}/{figure}/{id}
	/w/{query}/{relative}/{id}

## Languages Supported

- English (en)
- German (High) (de)
- Greek (Ancient) (gr)
- Dutch
- French
- Spanish
