# MediaLibrary
### Access read-only collections of the user's multimedia content.
## 概述
The Media Library framework provides a read-only Objective-C data model representing a user’s collections of images, audio, and video. The initial access point of the Media Library framework is MLMediaLibrary, which loads the user’s media into a hierarchical structure consisting of media sources, groups, and objects.

At the highest level, all content within a media library instance is categorized by media source. Conceptually, a media source respresents a single app, such as iTunes or Aperture. Each source contains a hierarchy of media groups that originates from a root group. These groups consist of media objects—individual files containing a piece of media such as a photo, song, or movie. Only one copy of each object exists within a media library instance, but an object can be referenced by multiple groups from a single source. The structure of the group hierarchy is specific to each media source.
