**Notice: Development on this repository is currently on pause during our v3 rearchitecture. Please see [storj/storj](https://github.com/storj/storj) for ongoing v3 development.**

# user.storj.io email service

This service enables Storj to allow (approved) 3rd party integrations to send emails to Storj users, without the need of sharing those users email addresses with the 3rd party.

This is a simple email forwarding service that resolves `[uuid]@user.storj.io` to the user's real email address on file with storj, and forwards the email along to that final destination. In this way, integrations can send an email to the user `uuid` without needing to know their real email address.

License
-------

Storj uuid-mailer
Copyright (C) 2017 Storj Labs, Inc

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see http://www.gnu.org/licenses/.
