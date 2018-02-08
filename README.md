# SingletonClassToastMassages

Create Singleton Class for Toast Message

Context Relevant:- context which needs to display your toast message. If you use this in the activity pass "this"
                   keyword or If you use in fragement pass as "getActivity()".
View:- Create a custom view and pass that view object to this.
gravity:- Pass the gravity position of the toaster. All the position has added under the Gravity class as the static
          variables . The Most common positions are Gravity.TOP, Gravity.BOTTOM, Gravity.LEFT, Gravity.RIGHT.
xOffset:- Horizontal offset of the toast message.
yOffset:- Vertical offset of the toast message.
Duration:- Duration of the toast show. We can set either Toast.LENGTH_SHORT or Toast.LENGTH_LONG


Toast messages are the most simple way of providing feedback to the user. By default, Android provide gray color
message toast where we can set the message and the duration of the message. If we need to create more
customizable and reusable toast message, we can implement it by ourselves with the use of a custom layout. More
importantly when we are implementing it, the use of Singelton design pattern will make it easy for maintaining and
development of the custom toast message class.
