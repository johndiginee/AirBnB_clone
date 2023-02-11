# 0x00. AirBnB clone - The console

In this project, we are tasked with building the following data models:

- User

- State

- City

- Amenity

- Place

- Review

These data models would be persisted using a json file storage. We create a `BaseModel` class which would be inherited from by the other data models. 

Each task is linked and will help you to:

- put in place a parent class (called `BaseModel`) to take care of the initialization, serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (`User`, `State`, `City`, `Place`…) that inherit from `BaseModel`
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine

### What’s a command interpreter?

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

## Resources

**Read or watch**:

- [cmd module](https://intranet.alxswe.com/rltoken/8ecCwE6veBmm3Nppw4hz5A "cmd module")
- [cmd module in depth](https://intranet.alxswe.com/rltoken/uEy4RftSdKypoig9NFTvCg "cmd module in depth")
- **packages** concept page
- [uuid module](https://intranet.alxswe.com/rltoken/KfL9TqwdI69W6ttG6gTPPQ "uuid module")
- [datetime](https://intranet.alxswe.com/rltoken/1d8I3jSKgnYAtA1IZfEDpA "datetime")
- [unittest module](https://intranet.alxswe.com/rltoken/IlFiMB8UmqBG2CxA0AD3jA "unittest module")
- [args/kwargs](https://intranet.alxswe.com/rltoken/C_a0EKbtvKdMcwIAuSIZng "args/kwargs")
- [Python test cheatsheet](https://intranet.alxswe.com/rltoken/tgNVrKKzlWgS4dfl3mQklw "Python test cheatsheet")
- [cmd module wiki page](https://intranet.alxswe.com/rltoken/EvcaH9uTLlauxuw03WnkOQ "cmd module wiki page")
- [python unittest](https://intranet.alxswe.com/rltoken/begh14KQA-3ov29KvD_HvA "python unittest")

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/815046647d23428a14ca.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230211%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230211T185915Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f40372fadb030af99f3ad55e7768999f182bb12abfdbee68dcd2a92cab77e7e4)

## Contributors

- [John Diginee](mailto:Johndbizz@gmail.com)

- [Dave Mcsavvy](mailto:davemcsavvii@gmail.com)
