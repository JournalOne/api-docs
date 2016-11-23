# Schema `website`

    {
      \_id: <string: guid>
      url: <object: url>,
      organisationId: <string: guid, foreign key>,
      info: {
        title: <string>
      },
      schedule: <object: schedule>,
      notification: <object: notification_settings>,
      latestCheck: <object: check>,
      profiler: <object: profiler_settings>, 
    }
