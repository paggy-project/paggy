# Commands (API and CLI)

| Command   | Alias             | Description                                                                                                                                                                            |
| --------- | ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| add       | pkg-act, -a       | Adds a package to library                                                                                                                                                              |
| remove    | pkg-deact, rm, -r | Removes a package from library, but not erases it                                                                                                                                     |
| delete    | erase, -d         | Deletes a package from library, if none dependant exists; if a dependant exists, it will be detached and deleted                                                                       |
| attach    | dep-act           | Attachs a package as dependency to another package, if attached package is compatible                                                                                                  |
| detach    | dep-deact         | Detaches a package as dependency from another package, if detached package is not the only compatible package or if a compatible package is known from a repository; online or offline |
| why       | pkg-w             | Shows reason why a package was added and/or attached                                                                                                                                   |
| about     | pkg-i             | Shows information about a package                                                                                                                                                      |
| all-about | pkg-iw, pkg-wi    | Shows any meta-data of a package; same as using why, about andy dep-show (`why about dep-show` `<pkg-name>`)                                                                           |
| show      | pkg-d, dep-show   | Shows dependencies of a package, only                                                                                                                                                  |
