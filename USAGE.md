<!-- Start SDK Example Usage -->


```typescript
import { Petstore } from "petstore";
import { CreatePetsResponse } from "petstore/dist/sdk/models/operations";

const sdk = new Petstore();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->