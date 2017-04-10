Explanation 7. Keeping your data safe

Two hashes walk into a bar, one was a salted.

One of the basic security rules is not to store user passwords in unencrypted form (easy to see and copy).

Instead of passwords written in "plain" text, so-called hashes are stored in databases (text transformed to fixed length). With a hash it is very difficult to recreate the password set by the user, but having the password we are able to compare whether the generated hash is equal to that stored in the database.

Salt is an additional parameter added to the user password, which secures the generated hash.
