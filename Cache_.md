investigation:
  travel_variant: direction forward
  experiments:
  - experiment:
      number:1
      input_data:
        buffer_size: 1Mb
      results:
        duration: 541 ms
  - experiment:
      number: 2
      input_data:
        buffer_size: 2Mb
      results:
        duration:  1100 ms
  - experiment:
       number: 3
       input_data:
        buffer_size: 4Mb
       results:
        duration:  2165 ms
  - experiment:
        number: 4
        input_data:
         buffer_size: 8Mb
        results:
          duration:  4373 ms
  - experiment:
        number: 5
        input_data:
         buffer_size: 12Mb
        results:
          duration:  6643 ms


 investigation:
   travel_variant: direction revers
   experiments:
  - experiment:
    number:1
    input_data:
    buffer_size: 1Mb
       results:
      duration: 420 ms
  - experiment:
    number: 2
    input_data:
    buffer_size: 2Mb
       results:
      duration:  831 ms
  - experiment:
    number: 3
    input_data:
    buffer_size: 4Mb
       results:
      duration:  1634 ms
  - experiment:
    number: 4
    input_data:
    buffer_size: 8Mb
       results:
      duration:  3677 ms
  - experiment:
    number: 5
    input_data:
    buffer_size: 12Mb
       results:
      duration:  4997 ms


investigation:
 travel_variant: random
experiments:
- experiment:
  number:1
  input_data:
  buffer_size: 1Mb
     results:
    duration: 1780 ms
- experiment:
  number: 2
  input_data:
  buffer_size: 2Mb
     results:
    duration:  3432 ms
- experiment:
  number: 3
  input_data:
  buffer_size: 4Mb
     results:
    duration:  6868 ms
- experiment:
  number: 4
  input_data:
  buffer_size: 8Mb
      results:
     duration:  16793 ms
- experiment:
  number: 5
  input_data:
  buffer_size: 12Mb
     results:
    duration:  22941 ms
